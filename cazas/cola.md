# Cola de caza — el árbol de nichos

Fuente de trabajo del programa de caza automatizado ([[automatizar-la-caza-de-winners]]). Cada sesión
(BR · IT · FR · RO · MX · CO) elige de acá **qué** cazar y en **qué modo**, y al terminar actualiza su nodo.

> ⛔ **Regla madre: el cero no descarta.** Un nodo pasa a `descartado-eje` solo después de (a) 4-5
> keywords nativas, (b) un nivel de subnichos perforado (modo B) y (c) `ad_active_status: ALL` mirado.
> Antes de eso vuelve como `superficial`. Los 🔴 los pone **el dueño**, nunca una sesión automática.

## Estados

| Estado | Significa | Qué hace la sesión con él |
|---|---|---|
| `virgen` | nunca se barrió | **prioridad 1** — modo A o B |
| `superficial` | se barrió con pocas keywords o un solo mercado | **prioridad 2** — modo B (perforar) |
| `profundo` | 4+ keywords nativas por mercado, subnichos mirados | solo modo C (operadores/agenda) |
| `ENTRAR` | hay molde y destino; el producto está en el catálogo o en camino | modo C: vigilar la ventana |
| `propio` | producto nuestro vivo en el nicho | modo C: vigilar competidores |
| `descartado-eje` | ese eje, en esos mercados, no da infoproducto modelable | no se toca; los hermanos sí |
| `🔴` | descarte permanente del dueño | no se toca |
| `🟡 <fecha>` | revisable en fecha | modo C cuando llega la fecha |

**Orden de elección:** `virgen` más viejo → `superficial` más viejo → `🟡` vencido. Dentro del mismo
estado, primero el nodo cuyo mercado coincide con la sesión. Una sesión no repite un nodo que otra
sesión tocó en los últimos 7 días.

---

## El árbol

Cargá acá tus nichos. Un nodo por nicho o subnicho (`nicho/subnicho`). Las keywords literales viven en
la página del nicho de tu wiki; acá va el conteo y la fecha. La columna Mercados dice a qué sesión
le toca (BR · IT · FR · RO · MX · CO). Si el árbol está vacío, las sesiones arrancan en modo A (huella) y lo van llenando con
los nichos que emergen.

| Nodo | Padre | Mercados | Estado | Cobertura | Próxima acción |
|---|---|---|---|---|---|
| recetarios | — | todas | 🔴 | — | **EXCLUIDO por el dueño en la instalación: no se busca, no se perfora, no se agrega como hijo** |
| actividades-adulto-mayor | — | todas | 🔴 | — | **EXCLUIDO por el dueño en la instalación: no se busca, no se perfora, no se agrega como hijo** |
| crochet | — | todas | 🔴 | — | **EXCLUIDO por el dueño en la instalación: no se busca, no se perfora, no se agrega como hijo** |
| mapas-visuales-mentales | — | BR | superficial | 2026-11-14 huella: 8 páginas, ninguna ≥ 10. 2026-11-15 (sesión local): Fluente com Legenda 170/240 y Educa Visual Digital 75/75 pasan la vara (2 tarjetas en bandeja); 4 jugadores en el formato | modo B: perforar avatares sin jugador (concursos PRF/TRT, enfermería, español para brasileños) y medir el hueco en MX/CO/AR/PE/CL |
| moldes-bordado-riscos | — | BR | virgen | 2026-11-14 huella: Riscos para Bordar 7/16 | modo B: re-medir y perforar subnichos (bordado, moldes de Natal) · apareció por huella el 2026-11-14 |
| guias-beneficios-inss-bpc | — | BR | descartado-eje | 2026-11-15 (sesión local, modo B): 7 keywords (guia BPC, BPC passo, INSS ebook, LOAS guia, guia aposentados, BPC autismo, aposentadoria pdf) + `ALL`; subnichos autismo, aposentados, salário-maternidade, Bolsa Família. Nadie ≥ 10: el gasto es de abogados (servicio) y la red «Implantes pelo SUS» (Growth Journey 29/43) es arbitraje de búsqueda. Único tester real: Guia dos Benefícios Sociais 0/7 a R$ 19,90 | eje «guía de trámite INSS/BPC» cerrado en BR; queda el hijo de autismo |
| guias-beneficios-inss-bpc/derechos-familias-autismo | guias-beneficios-inss-bpc | BR | virgen | 2026-11-15: «BPC autismo» da ~3.285 ads activos, casi todos de abogados; ningún infoproducto para familias visto | modo B: guía de derechos y trámites para padres de hijos con TEA (BPC, IPVA, IR, escuela); keywords sin «advogado» |
| habito-parar-de-fumar-corrida-5k | — | BR | virgen | 2026-11-14 huella: Parar de Fumar de Vez 0/6, Nasce um corredor 0/10 | modo B · apareció por huella el 2026-11-14 |
| organizacao-casa-metodo | — | BR | virgen | 2026-11-16 huella: Organize com Ju 13/14 | modo B: perforar subnichos (limpieza, rutina, plantillas) y medir PT/IT · apareció por huella el 2026-11-16 |
| preparacion-72h-apagon | — | BR | virgen | 2026-11-16 huella: red de 4 páginas, todas < 7 días | modo B: re-medir en 5 días · apareció por huella el 2026-11-16 |
| concursos-material-baixar | — | BR | virgen | 2026-11-16 huella: Lacuna Concursos ≥13/50 «Baixe Agora» | modo B: identificar qué vende · apareció por huella el 2026-11-16 |
| punto-croce-natale | — | IT | superficial | 2026-11-16 huella IT: Natale a punto ~41/50 (tarjeta en bandeja) | modo B: perforar punto de cruz por temas (animales, nombres, bordado) y medir FR/RO/PT · apareció por huella el 2026-11-16 |
| cuadros-diseno-quadri | — | IT | virgen | 2026-11-16 huella IT: Studio Quadri ≥13/≥50, oferta no identificada | modo B: identificar qué vende (plantilla vs físico) · apareció por huella el 2026-11-16 |
| red-atlante-visivo | — | IT | virgen | 2026-11-16 huella IT: learndigital.shop 0/50, Atlante Visivo del Cantiere 2/7 (atlas visuales profesionales, mezcla EN/IT) | modo B: re-medir en 5 días; ligar con red de mapas visuales de BR · apareció por huella el 2026-11-16 |
| musicogrammi-docenti | — | IT | virgen | 2026-11-16 huella IT: Silvia Moretti 0/39 (25 videos a 6,90) | modo B: re-medir en 5 días; juzgar marca personal · apareció por huella el 2026-11-16 |
| dime-falegnameria | — | IT | virgen | 2026-11-16 huella IT: Digital Corner 0/27 («80 progetti di dime») | modo B: re-medir en 5 días · apareció por huella el 2026-11-16 |
| kit-comptable-cahiers-2027 | — | FR | virgen | 2026-11-16 huella FR: Amélie Boissieu ≥32/50 piso (tarjeta en bandeja) | modo B: perforar contabilidad/gestión para autónomos por avatar (micro-empresa, asociación, hogar) y medir IT/PT/RO · apareció por huella el 2026-11-16 |
| jeux-dynamiques-300-pret-a-utiliser | — | FR | virgen | 2026-11-16 huella FR: Hugo Jean 24/27, ≈45 d (tarjeta en bandeja) | modo B: identificar el público (¡si es adulto mayor, excluido!) y medir IT/RO/PT · apareció por huella el 2026-11-16 |
| cricut-guides-visuels | — | FR | virgen | 2026-11-16 huella FR: Bibliothèque Créative 0/15 («+100 Guides Visuels Cricut», BRL) | modo B: re-medir en 3-4 días · apareció por huella el 2026-11-16 |
| ressources-neuro-imprimables | — | FR | virgen | 2026-11-16 huella FR: Boîte à Ressources Neuro 0/6 («+1 300 ressources à imprimer») | modo B: re-medir en 5 días, identificar el nicho (neurodiversidad/TDAH) · apareció por huella el 2026-11-16 |
| art-therapie-fiches-pdf | — | FR | virgen | 2026-11-16 huella FR: Manual de Arte Terapia 5/17 | modo B: re-medir y perforar · apareció por huella el 2026-11-16 |

---

## Trampas de keyword (no se repiten)

Cada sesión la lee antes de generar keywords y **agrega** las que descubre.

| Keyword / patrón | Por qué falla | Qué usar |
|---|---|---|
| `book` `novel` `read` (EN) | short-dramas (cientos de miles de resultados) | entregable + tema |
| `Google Sheets` / `sheets` | short-dramas | pares: `spreadsheet template`, `planilha controle` |
| keywords idénticas en ES/IT/PT (`farmacologia`, `peptide`, `dietoterapia`) | el mercado parece 3-8× más grande | la palabra que **no** se comparte; leer el idioma de cada creativo |
| siglas cortas (`EKG`) | spam de webnovelas | frase de 3+ palabras |
| préstamos del inglés (`barista`, `latte art`, `Meal Prep`) | traen anunciantes de otros países | la palabra nativa |
| keywords amplias en nichos de churn | solo devuelven las últimas 48 h | **angosto para ver la cola** |
| frases largas en `search_terms` | el matcher es **AND por token** | pares de palabras |
| huellas anchas en 🇧🇷 (`acesso imediato`, `apostila`, `kiwify`, precios) | decenas de miles de ads, los 50 primeros son de hoy: sirven para leer nombres de página, no para medir | barrer → anotar ~30 páginas → contar cada una con `page_ids` + `countries`; rinden `guia prático pdf`, `planilha pronta`, `ebook completo`, `material digital` |
| bloque `es` sin BO / EC / GT | subcuenta a los operadores andinos | `countries: ["MX","CO","AR","PE","CL","BO","EC","GT","ES"]` |
| `ad_creation_time` viejo sin impresiones | ads zombis | abrir el snapshot: «isn't in the Ad Library / no impressions» no cuenta |
| follow ads («Visit Instagram profile») | infl an la longevidad | la longevidad se lee **sobre el ad que vende** |
| `checklist pdf`, `kit digital completo` en BR | solo ads de las últimas 48 h; los lunes casi todo es tanda del fin de semana (cohorte 0) | contar por page_id y re-medir a los 4-5 días |
| `limit: 50` que devuelve 50 ads de hoy | cohorte truncada | reportar como piso, repetir con `page_ids` + `countries` |
| snapshot sin espera | `get_page_text` devuelve solo el encabezado | `wait` 4 s antes de leer |
| landing de operador 🇧🇷 | geo-redirige por idioma | el precio del mercado cazado se mira desde el checkout |
| página que devuelve **0 con `ALL`** | no está pausada: ya no existe | anotarla como desaparecida |
| un whale migra de página sin apagar el negocio | contar solo la página madre lo da por muerto | contar también las páginas hermanas de su ficha |
| página «cáscara» con nombre ajeno (Tudo sobre unhas vende mapas, moldes, proyectos) | el page_name no dice el nicho | leer el título del ad |
| página con tanda masiva de ayer (Mapas e Guias Visuais, 127 est.) y `limit:50` | los 50 son de hace ~22 h: cohorte no medible, no es 0 | reportar «≥50, cohorte no medible» y re-medir en 3-4 días |
| «Guia prático: …» de páginas genéricas en inglés (Growth Journey, Winning Mindset, Driven Forward, Goal Summit, Home Style) que pagan en **USD/PLN** | arbitraje de búsqueda (RSOC): el clic va a `track.*` → artículo gratis (`financeply.com`, `utm_medium=gs`); la longevidad es real pero no vende nada | descartar por embudo; si el título trae «Guia prático» y la moneda no es la local, abrir el destino antes de contar |
| `guide pdf`, `accès immédiat`, `paiement unique`, `bonus offerts guide` en FR | tandas de hoy de páginas cáscara en USD (Digital Skill, Online Packages, learndigital.shop, Download Studio) y ruido de coaches y short-dramas (PulseDrama, ReelyGo) | barrer para leer nombres y contar con `page_ids` + `countries`; rinden `fiches imprimables` y `cahier d'exercices` |
| `guida pdf`, `accesso immediato`, `ebook completo` en IT | solo ads de las últimas 48 h (estimado 1.471-5.041), tandas masivas de páginas cáscara (Digital Skill, Online Packages, learndigital.shop) | barrer para leer nombres de página y contar con `page_ids` + `countries`; el API no trae cuerpo ni URL, el producto sale del título |

## Operadores a seguir (modo C)

Fábricas multi-SKU y whales que muestran el próximo producto antes de que aparezca por keyword. Se
enumeran con `page_ids` + `countries`, siempre con el país. Cadencia: quincenal salvo que diga otra cosa.

| Operador | page_id | País | Por qué se lo sigue |
|---|---|---|---|
| Tudo sobre unhas (multi-SKU) | 106958424923732 | BR | 36 ads activos, 8+ SKU (mapas, moldes, proyectos); seguir SKUs nuevos |
| Riscos para Bordar | 396283016894466 | BR | 7/16 el 2026-11-14; re-medir |
| Mapas e Guias Visuais | 1394868680373327 | BR | 127 est. activos en una sola tanda; medir cohorte en 3-4 días |
| Guia dos Benefícios Sociais | 1415031105033080 | BR | 0/7 el 2026-11-15, guía a R$ 19,90, página nueva; re-medir ~2026-11-22 |
| Amélie Boissieu (Kit Comptable 2027) | 1363004406903385 | FR | ≥32/50 piso el 2026-11-16; seguir si se apaga o cambia de SKU; re-medir ~2026-11-23 |
| Hugo Jean (300 jeux & dynamiques) | 1382251738298675 | FR | 24/27, ≈45 d el 2026-11-16 (moneda BRL); re-medir ~2026-11-23 |
| Bibliothèque Créative (Cricut) | 1501332446389326 | FR | 0/15 el 2026-11-16 (tandas de 2-7 d); re-medir ~2026-11-19 |

## Rotación vigente

| Día | BR | IT | FR | RO | MX | CO |
|---|---|---|---|---|---|---|
| Lun | A huella | B perforar | C operadores | A huella | B perforar | C operadores |
| Mar | B perforar | C operadores | A huella | B perforar | C operadores | A huella |
| Mié | C operadores | A huella | B perforar | C operadores | A huella | B perforar |
| Jue | A huella | B perforar | C operadores | A huella | B perforar | C operadores |
| Vie | B perforar | C operadores | A huella | B perforar | C operadores | A huella |
| Sáb | C agenda | A huella | B perforar | C agenda | A huella | B perforar |
| Dom | lint de la cola | lint de la cola | lint de la cola | lint de la cola | lint de la cola | lint de la cola |

## Bitácora de la cola

Una línea por sesión, la más nueva arriba. La sesión la escribe **antes** de cazar (con «en curso») y
la completa al terminar.

| Fecha | Sesión | Modo | Nodo | Keywords corridas | Resultado | Nodo queda en |
|---|---|---|---|---|---|---|
| 2026-11-16 | FR | A huella (lun: C operadores sin operadores ni agenda FR → cola vacía → A) | — | guide pdf, planner imprimable, ebook complet, accès immédiat, fiches imprimables, modèles Notion, paiement unique, cahier d'exercices, bonus offerts guide + 10 conteos por page_id | 2 tarjetas (Kit Comptable 2027 ≥32/50 piso; 300 jeux & dynamiques 24/27); señales: Bibliothèque Créative 0/15, Boîte à Ressources Neuro 0/6 | 5 nodos virgen FR nuevos, 2 operadores |
| 2026-11-16 | IT | A huella (lun: B perforar sin nodos IT en la cola → A) | — | guida pdf, accesso immediato, planner stampabile, ebook completo + 12 conteos por page_id | 1 tarjeta (Natale a punto ~41/50); señales: Studio Quadri ≥13/≥50 oferta no identificada, Crescere Giocando 8/8 | 5 nodos virgen/superficial IT nuevos |
| 2026-11-16 | BR | A huella (lun) | — | planner imprimível, checklist pdf, kit digital completo, guia prático pdf, planilha pronta + 32 conteos por page_id | 1 tarjeta (Organize com Ju 13/14); señales: Lacuna Concursos ≥13/50 oferta no identificada, Cristina Maria 17/32 en 3 ofertas | 3 nodos virgen nuevos |
| 2026-11-15 | MX (tarde) | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda MX; sin 🟡 vencidos; nota: el nodo mapas-visuales-mentales (BR) pide medir el hueco en MX, queda para una corrida MX en día de semana | sin cambios |
| 2026-11-15 | RO (tarde) | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda RO; sin 🟡 vencidos | sin cambios |
| 2026-11-15 | FR (tarde) | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda FR; sin 🟡 vencidos | sin cambios |
| 2026-11-15 | BR (tarde) | lint de la cola (dom) | — | ninguna | 0 tarjetas; 5 nodos virgen/superficial BR de ≤ 2 días (ninguno > 30 d), sin 🟡 vencidos, agenda vacía; re-medición de Mapas e Guias Visuais vence 2026-11-17/18, de Guia dos Benefícios Sociais ~11-22 | sin cambios |
| 2026-11-15 | BR (sesión local) | B perforar | guias-beneficios-inss-bpc | guia BPC, BPC passo, INSS ebook, LOAS guia, guia aposentados, BPC autismo, aposentadoria pdf + `ALL` + 14 conteos por page_id | 0 tarjetas; Growth Journey 29/43 cae por arbitraje de búsqueda; mejor infoproducto: Guia dos Benefícios Sociais 0/7 | descartado-eje + hijo derechos-familias-autismo (virgen) |
| 2026-11-15 | CO (tarde) | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda CO; sin 🟡 vencidos; nota: mapas-visuales-mentales (BR) pide medir el hueco en CO, queda para corrida CO en día de semana | sin cambios |
| 2026-11-15 | CO | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda CO; sin 🟡 vencidos | sin cambios |
| 2026-11-15 | RO | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda RO; sin 🟡 vencidos | sin cambios |
| 2026-11-15 | FR | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda FR; sin 🟡 vencidos | sin cambios |
| 2026-11-15 | IT (tarde) | lint de la cola (dom) | — | ninguna | 0 tarjetas; sin nodos, operadores ni agenda IT | sin cambios |
| 2026-11-15 | IT | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda IT | sin cambios |
| 2026-11-15 | BR | lint de la cola (dom) | — | ninguna | 0 tarjetas; 4 nodos virgen BR de 1 día (ninguno > 30 d), sin 🟡 vencidos, agenda vacía; re-medición de Mapas e Guias Visuais (127 est.) vence 2026-11-17/18, de Riscos para Bordar y Tudo sobre unhas toca en la quincena (~11-28) | sin cambios |
| 2026-11-15 | MX | lint de la cola (dom) | — | ninguna | 0 tarjetas; la cola no tiene nodos, operadores ni agenda MX | sin cambios |
| 2026-11-14 | BR | A huella (sáb: C agenda sin operadores ni agenda → cola vacía → A; corrida de noche) | — | 6 huellas (guia prático pdf, planilha pronta, mapas mentais, ebook completo, acesso vitalício, material digital) + 16 conteos por page_id | 0 tarjetas; mejor: Riscos para Bordar 7/16 | 4 nodos virgen nuevos, 3 operadores |
| | | | | | | |
