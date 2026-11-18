# Bandeja — los ganadores del día, en tarjetas

Salida del programa de caza ([[automatizar-la-caza-de-winners]]). **Cada sesión deja acá como máximo
2 tarjetas por día**, una por producto ganador. Diez líneas cada una, nada más. La evidencia
completa (keywords, conteos, descartes) queda en `RAW/cazas-auto/` y **no se le muestra al dueño**
salvo que la pida.

> **Regla:** «pocos infoproductos ganadores por día y por mercado, por qué es ganador, qué se puede hacer
> con él, y el link de su biblioteca de anuncios. Nada de informes largos.» Si un día no sale ninguno que
> cumpla la vara, se escribe **una línea** («XX <fecha>: nada que pase la vara; se barrió X, Y, Z») —
> **nunca se rellena el podio**.

**Vara para tener tarjeta:** pasa el gate (no marca personal + embudo verificado o WhatsApp con la oferta
en el copy) **y** además cohorte de **10 o más** ads con 7+ días activos de un solo page_id. No se suman fanpages hermanas ni se compensa el volumen con la
longevidad de un ad suelto. Lo que pasa el gate pero no llega a la vara va como una línea de *señal*, no
como tarjeta.

**Cómo se revisa:** Claude muestra las tarjetas en el chat y **el dueño decide con palabras** — `Idea`
(se crea la ficha del producto) · `tirar` (a `descartados.md` con su motivo) · `re-cazar <fecha>` ·
`profundizar` (vuelve a [[cola]]). Nadie edita este archivo a mano. Las tarjetas decididas bajan al
histórico.

---

## Pendientes de revisión

<!-- TARJETAS-BR: la sesión BR inserta sus tarjetas del día justo debajo de esta línea -->

### 🎯 +2.000 Partituras para Piano e Teclado — Rafael Piano Fácil BR · `partituras-piano-teclado-co` · 2026-11-18 · sesión BR
- **Qué es:** pack digital «+2.000 Partituras para Piano e Teclado» y segundo gancho «Toque Piano/Teclado em 7 Dias»; ads en USD, precio no visible por API. Es la misma oferta de las tarjetas CO (11-16) e IT (11-17).
- **Por qué es ganador:** 31 de 50 anuncios activos con 7+ días (piso, la API topa en 50; 68 est. activos), un solo page_id, ≥20 con título en portugués inequívoco («e Teclado», «em 7 Dias»), 7 tandas de creación del 10-27 al 11-17 (≥ 3 fechas y ads de los últimos 30 días); mismo operador corriendo en BR + CO + IT = oferta validada en 3 mercados, BR el de mayor volumen.
- **Qué hacer:** verificar en la PC el embudo, el precio real y si «Rafael» es cara que vende (nombre de pila en la página; los títulos venden el pack, no una persona); si limpia, modelar «pack de partituras por instrumento» como producto propio para Portugal y Rumania (FR/IT ya tienen clones por medir); BR sirve como fuente del molde.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1109073548949200>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, marca personal). Snapshot: https://www.facebook.com/ads/library/?id=2293628624512404
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-18-br-C-operadores.md`

**Señales del día BR (2026-11-18, C operadores):**
- Tudo sobre unhas (106958424923732): 92 est. activos, los 50 visibles son de 11-15 a 11-18 (cohorte 0/50 piso, no medible); SKUs nuevos de la semana: Atividades Matemáticas 1º-5º ano, Fichas de Diagnóstico de Motos, Mini Livrinhos de Colorir +800, Moldes de Caixas, Megapack Moldes Infantis, 100 Artes para Copos 360°, Fichas de Treinos Femininos, 100 Instrumentais Cirúrgicos, Tabuada, Desenvolvimento Infantil. Re-medir ~11-22.
- Mapas e Guias Visuais (1394868680373327): se desinfló de 127 a 6 activos, todos 7+ d (6/6) y un solo SKU en USD («Teste antes de trocar a peça»); no pasa la vara.
- Guia dos Benefícios Sociais (1415031105033080): 7/7 (subió de 0/7 al cruzar 7 d); sigue < 10, eje INSS/BPC ya cerrado en BR.
- Camila Maia (582679418253715) 13/45 y Edital Master (125481670646964) 12/50 piso (16 el 11-17: los ads de SESAB/Saquarema del 11-10 cruzan 7 d hoy-mañana): ya con tarjeta.
- Fluente com Legenda (837003542818622) ≥22/50 piso, 236 est. (ya con tarjeta); su página gemela 996556976874285 0/2. Clon nuevo «Academia da legenda» (1521661844353417) 0/7, todo de 11-16/17, mismas reseñas «4,9/5».
- Nannyvarie (101372751885586) 39/46 estable, tarjeta vigente. Organize com Ju (1022767074413574) 11/16, tarjeta vigente; nombre de página + «Ju Saippa» en el título → juzgar marca personal en la PC.
- Riscos para Bordar 0/4 (ads de 11-15). Maria Eduarda (1389112280954409) apagó la tanda vieja: 0/6, todo de hoy.
- Ryu Nakamura (1237334109469401): ~1.229 est. activos, los 20 visibles de ≤ 2 d; marca personal (nombre = persona), no va a tarjeta; la re-caza del 11-24 es del dueño.

### 🎯 Apostilas digitales por concurso — Edital Master BR · `concursos-material-baixar` · 2026-11-17 · sesión BR (tarde)
- **Qué es:** apostilas digitales por concurso y cargo (EBSERH, TRT, CRP-RJ, Saquarema, IBGE…) a R$ 57-67, más cursos completos de R$ 127-257 como upsell visible; multi-SKU, una oferta por concurso.
- **Por qué es ganador:** 16 de 50 anuncios activos con 7+ días (piso, la API topa en 50), un solo page_id, 6 tandas de creación entre sep y nov, ≥1 ad de los últimos 30 días; nombre de página no es persona; titulares con precio en el ad.
- **Qué hacer:** verificar el embudo en la PC (checkout, precio real, cuánto es PDF y cuánto video); si cierra, modelar «apostila + simulado por concurso/cargo» en Italia (concorsi pubblici) y Portugal; en BR es un molde muy copiado (Tutoria EAD, Certiva, S.S Simulados).
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=125481670646964>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, marca personal). Snapshot: https://www.facebook.com/ads/library/?id=29431519586480208
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-br-B-concursos-material-baixar-tarde.md`

### 🎯 Mapas de revisión para concursos TJSP — Camila Maia BR · `concursos-material-baixar` · 2026-11-17 · sesión BR (tarde)
- **Qué es:** pack de mapas mentales de revisión por concurso («221 Mapas de Revisão para Oficial de Justiça TJSP», «465 Mapas… Escrevente TJSP»); PDF presumible, precio no visto (BRL).
- **Por qué es ganador:** 13 de 36 anuncios activos con 7+ días (1 en el borde), un solo page_id, un solo titular repetido por SKU, creados de sep a nov (≥ 8 fechas), ≥1 ad de los últimos 30 días.
- **Qué hacer:** verificar en la PC si la cara de la dueña vende (nombre de página = persona → posible marca personal) y el embudo; si es producto sin cara, es el hueco «concursos» del nodo mapas-visuales-mentales: modelar «N mapas por cargo» para concorsi (IT) o PT.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=582679418253715>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, marca personal). Snapshot: https://www.facebook.com/ads/library/?id=29966344776283690
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-br-B-concursos-material-baixar-tarde.md`

**Señales del día BR (tarde):**
- Lacuna Concursos (1173569735845788) 10/22, todos «Baixe Agora»: oferta sigue sin identificarse.
- Tutoria EAD (113895654244531) 6/50 piso y Apostilas Digitais (104515792564994) 5/33: apostila por municipio, embudo WhatsApp «Converse conosco»; S.S Simulados (698360183366595) 9/50 piso: re-medir ~11-19.
- Certiva Concursos (1312360308622118) 0/50 piso, todo de 1-2 días, apostilas R$ 27,90: re-medir ~11-24.

BR 2026-11-17: nada que pase la vara; se barrió parar de fumar, deixar de fumar, tabagismo, plano de treino corrida 5k, planilha treino corrida, correr 5km iniciante. Señales: Maria Eduarda (1389112280954409) 1/50 piso, «Kit Completo para Corredores por R$ 5», tandas diarias de creación: re-medir ~11-20 (juzgar marca personal). Parar de Fumar de Vez (1436509976219606) 0/6, guía 30 días Hotmart, hace ~3 d: re-medir ~11-20. Nasce um corredor 0/12 y Corrida em Evolução 0/36 (todo de hoy). Informe: `RAW/cazas-auto/2026-11-17-br-B-habito-parar-de-fumar-corrida-5k.md`

### 🎯 Bordado en papel · presentes de Natal — Nannyvarie BR · `moldes-bordado-riscos` · 2026-11-16 · sesión BR (tarde)
- **Qué es:** oferta de bordado en papel para regalos navideños hechos a mano (¿moldes/riscos + guía o mini-curso?); producto exacto y precio no vistos (BRL).
- **Por qué es ganador:** 39 de 43 anuncios activos en BR con 7+ días, un solo page_id y un solo creativo repetido; tandas de creación 10-21, 10-26 y 11-15/16; longevidad máx. ≈ 25 días; nombre de página no es una persona.
- **Qué hacer:** observar y verificar el embudo en la PC; si es digital, modelar el molde «bordado en papel + Navidad» en PT, IT, FR, RO; estacional, ventana hasta ~mediados de dic.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=101372751885586>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, marca personal). Snapshot: https://www.facebook.com/ads/library/?id=1110083021863954
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-br-B-moldes-bordado-riscos-tarde.md`

**Señales BR 2026-11-16 (tarde):** Riscos para Bordar cayó de 7/16 a 0/4 (se apagó la tanda vieja). Bordado Criativo (1289620830901567) 4/20, dos tandas de 8-9 ads de hace 1-3 días («Crie peças lindas em 15 minutos»): re-medir ~11-20. Mariana Duarte (1277206485465907) 0/12, «Bordado no Papel + 500 riscos», tanda de hace 3-4 días: re-medir ~11-20. Terapia das Cores (110206475291825) ~23 ads de hace 2 días en USD, 0 de cohorte. Rabelo Arte (321796351025395) tanda de hoy, «100 riscos por R$ 47».

**BR 2026-11-16 · Método Casa Leve 60 — Organize com Ju** · `sin-revisar`
- Por qué gana: 13 de 14 anuncios activos en BR con 7+ días, un solo page_id y una sola oferta («Casa Leve 60»); 3 tandas de creación (11-06, 11-07, 11-15). Longevidad máx. ≈ 9 días: oferta joven.
- Qué vende: método de organización del hogar con plantillas «v6» y «aulas rápidas y 100 % prácticas» (¿mini-curso grabado?). Precio no visto.
- Embudo: no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, y si «Ju» pone la cara).
- Gancho: «Método Casa Leve 60» · «Aulas Rápidas e 100% Práticas».
- Qué se puede hacer: llevar el molde a Portugal e Italia (orden y limpieza del hogar, evergreen); mismo formato de plan de 60 días.
- Biblioteca: <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1022767074413574> · Snapshot: https://www.facebook.com/ads/library/?id=1889373632059546
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-br-A-huella.md`

**Señales BR 2026-11-16:** Lacuna Concursos (1173569735845788) ≥13/50 piso, 12 fechas desde 10-06, todos «Baixe Agora»: no se sabe qué vende. Cristina Maria (914677635067969) 17/32 pero en 3 ofertas de umbanda (sabonetes 9, estampas 4, oferendas 4): ninguna llega a 10. Lanzamientos < 7 días a re-medir: Reescrevendo seu Caminho (numerología, 50+ piso), Fernando Contador (22, USD), Tchau Fralda (9), Cadu Oliveira (16), Família Preparada (13, USD, tema apagón 72 h).

**BR 2026-11-15 · Kit +300 Mapas Mentais de Inglês — Fluente com Legenda** · `sin-revisar`
- Por qué gana: 170 de 240 anuncios en BR con 7+ días, sobre una sola oferta; campaña apilada de jul a oct.
- Qué vende: kit digital de +300 mapas mentales de inglés imprimibles, R$ 47–97, bonos y garantía 7 días.
- Embudo: directo a landing con precio y checkout, sin marca personal. Escalera n/e.
- Gancho: «Aprenda e revise inglês sem complicação com +300 mapas mentais imprimíveis.»
- Qué se puede hacer: mismo molde en otro idioma o avatar (el inglés lo domina esta página, con una versión en español de pocos anuncios); hueco de arbitraje sin medir.
- Biblioteca: <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=837003542818622> · Snapshot: https://www.facebook.com/ads/library/?id=1407719990900998
- Evidencia: `RAW/cazas-auto/2026-11-15-br-A-huella-mapas-visuales.md`

**BR 2026-11-15 · Mapa Fácil da Reforma Tributária — Educa Visual Digital** · `sin-revisar`
- Por qué gana: 75 de 75 anuncios en BR con 7+ días, una oferta en 3 dominios; jul–oct escalonado.
- Qué vende: mapas mentales de IBS, CBS e Imposto Seletivo, R$ 27, archivos digitales.
- Embudo: página de producto con precio. Sin marca personal. Escalera n/e.
- Gancho: «A Reforma Tributária já está trazendo novas regras, siglas, cálculos e mudanças nos documentos fiscais.»
- Qué se puede hacer: mismo molde en otro nicho profesional con comprador urgente. Atada a una ley brasileña: no se exporta y vence.
- Biblioteca: <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=BR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1125950840608312> · Snapshot: https://www.facebook.com/ads/library/?id=2077451369528717
- Evidencia: `RAW/cazas-auto/2026-11-15-br-A-huella-mapas-visuales.md`

**Señales BR 2026-11-15:** Carla Figurinhas (973418882530327) 51/54, pack de stickers a R$ 5,99, piso de precio. Inglês Fluente (1477324255655344) 310/380, descartada por formato (curso de 8 semanas con plataforma).

BR 2026-11-14: nada que pase la vara; se barrió guia prático pdf, planilha pronta, mapas mentais, ebook completo, acesso vitalício, material digital (16 páginas contadas; la mejor, Riscos para Bordar 7/16).

**Señales del día BR**
- Riscos para Bordar (moldes de bordado, page_id 396283016894466): cohorte 7/16 en BR, a 3 de la vara; re-medir en unos días. Embudo no verificado desde la nube.
- Red de «mapas visuales/mentais» (SharkAprova R$ 27,90, Mapa Mestre, Francês do Zero à Fluência, Tudo sobre unhas con 36 ads y 8+ SKU): nicho emergente, ninguna pasa 10 todavía.
- Mapas e Guias Visuais (127 ads est. en una sola tanda de hace ~22 h): cohorte no medible aún; re-medir en 3-4 días.

<!-- TARJETAS-IT: la sesión IT inserta sus tarjetas del día justo debajo de esta línea -->

IT 2026-11-17 (tarde): nada que pase la vara; se barrió atlante visivo, mappe mentali, schede didattiche pdf, progetti legno pdf (ninguna página con cohorte de 7+ d: todo empezó desde el 11-13).
- Señales tarde IT: Tecnica Visiva (1417504704779124) 0/100, red de atlas técnicos visuales «+300 mappe» desde 11-16, re-medir ~11-21; Shop Plans (1354104621129963) 0/40 planos de casas/pérgolas desde 11-13, re-medir ~11-20; Lorenzo Santoro / Luiggi Totti «3 libri a €18,90» 0/44 y ≥20, páginas hermanas, producto sin identificar; Oriana Viscontii «inglese con mappe mentali» 0/20; Inglese Visuale 0/10.

### 🎯 +1.000 Spartiti per Pianoforte/Tastiera — Rafael Piano Fácil IT · `partituras-piano-teclado-co` · 2026-11-17 · sesión IT
- **Qué es:** pack de +1.000 partituras en PDF para piano/teclado (en español «+2.000 Partituras»); precio no visto (cuenta en USD).
- **Por qué es ganador:** 34 de 45 ads activos en IT con 7+ días (45 = total, no truncado), un solo page_id; solo los ads con título en italiano son 10 de ≈14 (el resto es creatividad en español que también llega a IT); 9+ fechas de creación, 5 ads nuevos ayer; longevidad máx. ≈ 34 días; nombre de página = nombre de pila (sin cara en los títulos).
- **Qué hacer:** modelar tal cual (kit de partituras para piano/teclado por género); es la misma oferta que corre en CO (tarjeta del 2026-11-16) y en BR, así que ya hay molde en tres mercados; destinos a medir: FR, RO, PT; en IT el cohorte italiano está en el borde (10): re-medir ~11-24.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=IT&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1109073548949200>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1471667681591285
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-it-C-operadores.md`

**Señales del día IT 2026-11-17**
- Studio Quadri (721617357705716): re-medido, sube a 11/50 piso en IT (tarjeta ya en bandeja; tandas 11-09, 11-12, 11-16); oferta aún sin identificar.
- Natale a punto (1288220937718528): 40/50 piso, longevidad ≈ 15 d, sigue activa (tarjeta ya en bandeja).
- Crescere Giocando (1009883552206401): 7/8 (a 3 de la vara; «300 attività + 5 bonus», EUR); re-medir.
- Silvia Moretti (1519553207903758) 0/50 piso y Digital Corner (1358074294058687) 0/36: lanzamientos de 1-5 días; cruzan 7 d desde ~11-20; Silvia Moretti: 25 musicogrammi a 6,90 € y pack 12,90 €, mucho test de copy.
- Acordes en Claro (1205940002609789): ≥50 ads en italiano en IT (est. 672), todos ≤ 6 d: cohorte no medible; ya tiene tarjeta en CO.
- 300 Mapas Mentales (18/22) y Hugo Jean (5/5) aparecen en IT con creativos en español/francés: fuga de segmentación, no cuentan como evidencia IT.

### 🎯 Progetta i tuoi quadri in 15 minuti — Studio Quadri IT · `cuadros-diseno-quadri` · 2026-11-16 (tarde) · sesión IT
- **Qué es:** herramienta/plantilla para diseñar cuadros de pared en 15 minutos; formato y precio no vistos (cuenta en USD); podría ser físico: verificar.
- **Por qué es ganador:** 10 de 50 ads activos en IT con 7+ días (50 = piso del API, estimado 170), un solo page_id y un solo título; 3 tandas de creación (11-09, 11-12/13 y ~22 ads hoy); longevidad máx. ≈ 7,9 días, sin marca personal en el nombre de página.
- **Qué hacer:** identificar primero qué vende (plantilla digital vs producto físico); si es digital, modelar como kit de plantillas/arte imprimible; destinos a medir: FR, PT/BR, RO; en el borde de la vara (10 justos, longevidad corta): re-medir en 5 días antes de decidir.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=IT&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=721617357705716>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1090851587283215
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-it-B-cuadros-diseno-quadri-tarde.md`

**Señales del día IT (tarde) 2026-11-16**
- Quadri Facili (1361523357050535): «Atlante Visivo della Strumentazione», BRL, ~22 ads de 11-08 a 11-10 y hoy 0 activos: apagó todo; ligado a red-atlante-visivo.
- Wallify Studio (571188336087784): tienda ecommerce multi-producto (ropa, posters 29-34 € «Download Immediato»); físico, no es infoproducto.

### 🎯 Natale a Punto Croce · 300 schemi da stampare — Natale a punto IT · `punto-croce-natale` · 2026-11-16 · sesión IT
- **Qué es:** PDF imprimible de 300 patrones de punto de cruz navideño; precio no visto (cuenta en USD).
- **Por qué es ganador:** ~41 de 50 ads activos en IT con 7+ días (50 = piso del API), una sola oferta, 4 tandas de creación desde ~11-02 y 5 ads nuevos ayer; longevidad máx. ≈ 14 días; sin marca personal.
- **Qué hacer:** modelar tal cual (kit de patrones imprimibles); destinos: FR (Noël point de croix), RO, PT/BR; es estacional (Navidad), ventana hasta ~mediados de dic; ángulo «patrones listos para imprimir», bonos.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=IT&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1288220937718528>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1168752989131371
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-it-A-huella.md`

**Señales del día IT 2026-11-16**
- Studio Quadri (721617357705716): ≥13/≥50 piso en IT, tanda de 13 ads de ~11-08 aún activos; título «Progetta i tuoi quadri in 15 minuti»; no se sabe si vende plantillas digitales o producto físico: verificar en la PC.
- Crescere Giocando (1009883552206401): 8/8 en IT, «300 attività per crescere giocando» (a 2 de la vara); re-medir.
- Edukhair academy (255071511012533): 6/28, «garanzia soddisfatti o rimborsati», oferta no identificada.
- Digital Corner (1358074294058687, «80 progetti di dime», plantillas de carpintería) 0/27 y Silvia Moretti (1519553207903758, 25 musicogrammi a 6,90) 0/39: lanzamientos de 2-5 días; re-medir en 5 días. Silvia Moretti: posible marca personal, a juzgar en el snapshot.
- Redes de páginas cáscara con tandas masivas de hoy (Digital Skill 0/36, learndigital.shop «Visual Atlas» 0/50, Online Packages 0/19, Digital Master 1/11): sin cohorte aún.

IT 2026-11-15 (tarde): domingo, lint de la cola; sin nodos, operadores ni agenda IT vencidos; nada que pase la vara.

<!-- TARJETAS-FR: la sesión FR inserta sus tarjetas del día justo debajo de esta línea -->

### 🎯 12 manuels + 5 outils pour l'atelier — Car Station FR · `manuels-atelier-mecanique-fr` · 2026-11-17 (tarde) · sesión FR
- **Qué es:** pack de 12 manuales de reparación (cajas automáticas y averías «cada avería tiene su capítulo») + 5 herramientas para talleres mecánicos; probablemente PDF; precio no visto (cuenta en USD, operador no francés).
- **Por qué es ganador:** 24 de 37 ads activos en FR con 7+ días (no truncado), un solo page_id; 17 llevan el título exacto «12 manuels + 5 outils» y el resto son ángulos de la misma oferta; ≥ 6 fechas de creación (10-30 → 11-14), 8 ads nuevos en los últimos 4 d, longevidad máx. ≈ 17 d por API; página sin cara.
- **Qué hacer:** modelar «manuales técnicos de reparación + herramientas para talleres» (conocimiento, no objeto); destinos a medir: IT, PT/BR, RO (talleres/mecánicos); el contenido técnico se reescribe por mercado.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1124004904129860>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1508479801149051
- Score n/4 (1/4 provisorio: longevidad ≈ 17 d; hueco IT/PT/RO sin medir; ⚠ verificar que no sea producto físico) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-fr-A-huella-tarde.md`

**Señales del día FR tarde 2026-11-17**
- Belle Plume (1521932121003975): 16/18 con 7+ d pero en 4 SKUs («40 fiches CRPE», «40 séquences d'images CP-CM2», «40 séances d'arts plastiques», «Éveil musical 30 activités»); ninguno ≥ 10; molde «40 X prêtes à l'emploi».
- Gavin Campbell (1167821096418693): 28/28 con 7+ d (≈ 118 d), solo «Contactez-nous», oferta no identificable (¿servicio/lead-gen?); no pasa el gate.
- Pharmacologie Simplifiée (1391162887408497): 0/4, «Top 200 des médicaments en images» (tanda de hoy, multilingüe).
- Solutions Numériques en Ligne 0/7 («+170 activités d'attention CP-CM2»), Nara Costa 0/6 («150+ cartes de colorimétrie», BRL), Sunday Budget 0/1 (plantilla Google Sheets).

### 🎯 520+ cartes mentales pour parler espagnol — Espagnol Illustré FR · `idiomas-cartes-mentales-a1-c2` · 2026-11-17 · sesión FR
- **Qué es:** pack de 520+ mapas mentales/fichas de español para francófonos (6 recorridos A1→C2, «una regla = una página»), PDF o impreso, con 3 bonus (diccionario de falsos amigos, guía de pronunciación, planner 30 días); precio no visto (cuenta en USD, operador no francés).
- **Por qué es ganador:** 15 de 26 ads activos en FR con 7+ días (no truncado), un solo page_id y una sola oferta; creaciones en 3 tandas (11-01, 11-05, 11-12) y longevidad máx. ≈ 17 días por API; nombre de página = producto, sin cara. Hay un segundo jugador en el molde: Céline Moreau «+300 cartes mentales · A1 à C2» 3/10. 0 ads de esta página en IT/PT/RO.
- **Qué hacer:** modelar el molde «mapas mentales de idiomas por nivel A1-C2»; destinos a medir y llevar: IT (español para italianos), PT/BR (español para brasileños), RO; conecta con la red de mapas visuales de BR/MX. Un ad apunta a «espagnol à 60 ans» (solo un ángulo, el producto no es actividad de adulto mayor).
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1435820002945205>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1020762231046294
- Score n/4 (1/4 provisorio: longevidad ≈ 17 d; hueco IT/PT/RO sin medir a fondo) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-fr-A-huella.md`

### 🎯 Atlas thérapeutique visuel — PsiOS FR · `atlas-psicoterapia-ro` (familia) · 2026-11-17 · sesión FR
- **Qué es:** atlas visual / mapas mentales terapéuticos para psicoterapeutas (también «Mappe mentali terapeutiche» en IT, «Mapas mentales terapéuticos» en ES y «250+ therapeutic mind maps» en EN, más «100 mapas visuales de neurociencia del trauma»); probablemente PDF; precio no visto (cuenta en USD).
- **Por qué es ganador:** 10 de 33 ads activos en FR con 7+ días **contando solo los creativos en francés** (el resto es IT/ES/EN), un solo page_id; longevidad por API ≈ 8 d; la cohorte es **borde** (10 exactos) y 9 de los 10 son de una misma tanda (11-08), página con ≥ 6 fechas de creación entre todos los idiomas y ads desde hace 54 días; sin cara, nombre = producto. Misma familia que Atlas Terapeutic Vizual (RO, tarjeta del 11-16).
- **Qué hacer:** modelar «atlas visual de herramientas para terapeutas»; el molde ya corre en RO y FR (y PsiOS lo prueba en IT/ES/EN): destinos a medir IT, PT/BR; re-medir ~2026-11-21 para ver si la tanda sigue viva.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=111707335304926>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=2189842628635708
- Score n/4 (no evaluado; cohorte en el borde) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-fr-A-huella.md`

**Señales del día FR 2026-11-17**
- Biblioteca Práctica (1415895891603865): 8/24 en FR, «Le Classeur Antisèche · 72 fiches de mixage» (mezcla de audio, COP); a 2 de la vara, re-medir ~11-20.
- Manuels Illustrés (1412630685262258): 0/21, fábrica multi-SKU de «manuels illustrés» (CRPE, CRFPA, VTC, Contrôleur finances publiques, Obligations); todo ≤ 5 d; re-medir ~11-20.
- Céline Moreau (1367953336410558): 3/10, «+300 cartes mentales A1-C2» (segundo jugador del molde de idiomas).
- The Horsemanship Club (1303084746212441): 6/43 en creativos FR (≈ 36 en inglés = fuga), curso de equitación «220 leçons»; no cuenta como cohorte FR.
- Simone Longo Infirmière 5/10 (BRL), Laura Martin 13/28 repartido en 3 ofertas (no una sola), Atelio Guides 0/18, Les Carnets Pratiques 0/8, Atelier Nova 0/5 (Atlas Biomécanique), tandas de hoy.

### 🎯 Kit Comptable Pratique 2027 · 7 cahiers + 6 bonus — Amélie Boissieu FR · `kit-comptable-cahiers-2027` · 2026-11-16 · sesión FR
- **Qué es:** kit de 7 cuadernos de contabilidad práctica 2027 + 6 bonus, presumiblemente PDF imprimible; precio no visto (cuenta en USD, operador no francés).
- **Por qué es ganador:** ≥32 de 50 ads activos en FR con 7+ días (50 = piso del API, estimado 70), un solo page_id y una sola oferta; tandas de creación escalonadas desde hace ~21 días y 2 ads nuevos hoy; copy de producto sin cara visible en los títulos (nombre de página = persona: juzgar en el snapshot).
- **Qué hacer:** modelar el molde «cuadernos de gestión/contabilidad para autónomos y pymes» (el contenido fiscal es local: se reescribe por país); destinos a medir: IT, PT, RO; ángulo «kit del año nuevo 2027», bonus apilados; estacional (cierre/inicio de año).
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1363004406903385>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=2058595798877775
- Score n/4 (≤ 1/4 provisorio, hueco de arbitraje sin medir) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-fr-A-huella.md`

### 🎯 300 jeux & dynamiques prêts à utiliser — Hugo Jean FR · `jeux-dynamiques-300-pret-a-utiliser` · 2026-11-16 · sesión FR
- **Qué es:** pack de 300 juegos y dinámicas listos para usar (público exacto no identificado: ¿animadores, profesores, entrenadores?); precio no visto (cuenta en BRL: molde brasileño traducido al francés).
- **Por qué es ganador:** 24 de 27 ads activos en FR con 7+ días (no truncado), un solo page_id y una sola oferta; 8+ fechas de creación distintas, longevidad máx. ≈ 45 días, 3 ads de hace ~5 días; sin cara en los títulos (nombre de página = persona: juzgar en el snapshot).
- **Qué hacer:** modelar tal cual (pack de fichas/juegos imprimibles); destinos a medir: IT, RO, PT; ⚠ si el público resulta ser animadores de adultos mayores cae en un nicho excluido: verificar en la PC antes de decidir.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1382251738298675>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=2005025430179720
- Score n/4 (1/4 provisorio: longevidad ≈ 45 d; hueco sin medir) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-fr-A-huella.md`

**FR 2026-11-16 (tarde):** nada que pase la vara; se barrió comptabilité auto-entrepreneur, cahier comptabilité association, budget familial tableur, facture devis modèle, budget mensuel pdf. Señales: Kit Comptable (Boissieu) sube a 41/50 piso, sigue siendo el único infoproducto de gestión en FR; Mon Mois en Clair (1443595892171798) 0/2, planner mensual en USD, tanda de hoy: re-medir ~11-21. Informe: `RAW/cazas-auto/2026-11-16-fr-B-kit-comptable-cahiers-2027-tarde.md`

**Señales del día FR 2026-11-16**
- Bibliothèque Créative (1501332446389326): 0/15 en FR, «+100 Guides Visuels pour Cricut Design Space» (moneda BRL, molde BR traducido); tandas de hace 2-7 días; re-medir en 3-4 días.
- Boîte à Ressources Neuro (1345809441959313): 0/6 en FR, tanda de hoy, «+1 300 ressources prêtes à imprimer», pago único; re-medir en 5 días.
- Manual de Arte Terapia (1213147361873813): 5/17 y Elena Martin (1058993513953988, +2 000 modelos de tricot): 5/16; a 5 de la vara; re-medir.
- PathoFiches (1368093956386045, fiches de enfermería) 4/8; Studio Quadri 0/8 en FR (tanda de hoy; en IT ≥13/≥50).
- Tandas de hoy de páginas cáscara sin cohorte: Acordes en Claro (19+), Download Studio (13+), Digital Skill, learndigital.shop, Online Packages, Atelio Guides.

FR 2026-11-15: domingo, lint de la cola; sin nodos, operadores ni agenda FR vencidos; nada que pase la vara.

<!-- TARJETAS-RO: la sesión RO inserta sus tarjetas del día justo debajo de esta línea -->

RO 2026-11-17 (tarde): nada que pase la vara; se barrió jurnal pdf, șabloane Canva, limba engleză pdf, pachet digital, metodă pas cu pas, Metoda Genius, curs video înregistrat (+ 7 conteos por page_id). Informe: `RAW/cazas-auto/2026-11-17-ro-B-nodos-nuevos-tarde.md`

**Señales del día RO (tarde) 2026-11-17**
- Genius Mentor (1202927619580444): 22/50 piso con 7+ días, pero 19 son promos «Black Friday −50 %» y el anuncio base «Învață de 5x Mai Rapid prin Metoda Genius» solo tiene 3 de 7+ d (el resto 5-8 d); página hermana Genius Bac (878536441990147) 10/37. RON. Oferta no identificada (el nombre sugiere mentoría/curso): verificar en la PC si es curso grabado/PDF; si lo es, es el candidato más cerca de la vara.
- Rowan House Press (103448682074390): 0/50 piso, tanda del 11-16 (~19 h) de ~25 libros «explicat prin desene» (Istoria artei, Biologie 108 pagini, Matematica, Psihologie, Frigotehnist, Electrician), USD, «Preț de lansare» y vista previa de páginas antes de descargar: mismo molde que Studio Facile y Atlas Terapeutic Vizual; re-medir ~2026-11-21.
- Mesa Ligera (1219245414615500): 4/38, multi-SKU en EUR («Psihiatria pe fișe F00–F98» ≈ 10 ads de ayer, SSM, «Un an la grădiniță: 36 de săptămâni», raport descriptiv); ningún SKU ≥ 10 con 7+ d; re-medir ~2026-11-21.
- Ioana Dumitrescu (1202173556320802): 5/10, pachete de postări para redes («Un an de postări într-un singur pachet», EUR); re-medir ~2026-11-21.
- Ioana Radu (1357933167412610): 0/20, «50 de instrumente pentru dislexie» imprimibles (CLP), todo del 11-16/17.

RO 2026-11-17: nada que pase la vara; se barrió contabilitate caiete, fișe de lucru pdf, gata de predat, șabloane Excel, ghid practic pas cu pas (+ PFA y buget familie dan 0). Informe: `RAW/cazas-auto/2026-11-17-ro-B-contabilidad-cuadernos-ro.md`

**Señales del día RO 2026-11-17**
- Edulabs Resources (1057793390758198): 15/48 con 7+ días por API, pero ≈ 8 son creativos en inglés y los de rumano (Religie «6 volume + 5 bonusuri») ≤ 7; multi-SKU «gata de predat» para profesores, USD; re-medir ~2026-11-21 contando solo rumano.
- Contador en Acción (1418159758044206) 3/21 y MARCO MEDIA (1350956431432254) 0/8: kit contable RO aún sin cohorte; re-medir ~2026-11-22.
- Diagram Books (1499263639932513) 0/31 y Learning Fast (1469659026222538) 0/15: cuadernos de oficios «+ 2 cărți cadou», tandas ≤ 6 d.
- Liveno by Iva Milan (1259209043938308): 0/50 piso, el más viejo ≈ 6,2 d, multi-SKU de proyectos lemn/metal; re-medir ~2026-11-20.

### 🎯 Atlas Terapeutic Vizual — Atlas Terapeutic Vizual RO · `libros-visuales-en-imagenes-ro` · 2026-11-16 (tarde) · sesión RO
- **Qué es:** atlas visual para psicoterapeutas en rumano (12 enfoques terapéuticos, 32 metáforas visuales, índice y flujogramas para sesión, búsqueda de tema); probablemente PDF/atlas digital; precio no visto.
- **Por qué es ganador:** 11 de 50 ads activos en RO con 7+ días (50 = piso del API, estimado 55), un solo page_id y un solo producto con ≥ 6 fechas de creación (11-05 a 11-15); longevidad máx. ≈ 11,7 días por API; nombre de página = producto, sin cara. Cuenta en ARS (operador que traduce al rumano). Misma familia que los atlas visuales de MX/IT.
- **Qué hacer:** modelar el molde «atlas visual de herramientas para profesionales» en psicología/terapia; el RO ya lo corre, destinos a medir: IT, FR, PT/BR; la cohorte está en el borde (11) y crece: re-medir ~2026-11-20.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=RO&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1408033785736088>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1139477258580093
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-ro-B-libros-visuales-en-imagenes-ro-tarde.md`

**Señales del día RO (tarde) 2026-11-16**
- Studio Facile (1232011766670582 y 1272162682644374): 39/48 y 15/50 piso con 7+ días desde 10-28, pero ~25 temas y ninguno ≥ 10; si es catálogo único, la lectura cambia: verificar en la PC.
- Pagina de Nursing (340055433511635): ≈ 20/21 con 7+ días en RON («ghiduri ilustrate» de nursing, Black Friday −70 %), pero mezcla clipboards, insignias y paquetes físicos: verificar si el guion es PDF o libro impreso.
- Ready Resources (1440348585824077): «Biologie clasa a IX-a – noua programă», 5/30 con 7+ días, ~20 ads de hoy (USD, «gata de proiectat»): re-medir ~2026-11-20.
- Impulso Digital (1339782509218557): «300 de hărți mentale de asistent medical» (BRL), 5 ads de hoy, 0 de cohorte; misma oferta de 300 Mapas Mentales (MX): re-medir ~2026-11-21.

RO 2026-11-16: nada que pase la vara; se barrió ghid pdf, acces imediat, planner imprimabil, fișe imprimabile, ebook complet, caiet exerciții, șabloane gata, descarcă ghidul (14 páginas contadas; la mejor, Studio Facile ≥17/54 y 38/48 pero repartido en ~20 temas). Informe: `RAW/cazas-auto/2026-11-16-ro-A-huella.md`

**Señales del día RO 2026-11-16**
- Studio Facile (1272162682644374 y 1232011766670582): libros «X în imagini» (USD), 38/48 y ≥17/54 con 7+ días, pero ningún tema ≥10 (Sudura, Contabilitatea, Teoria muzicii 5 c/u); si es un catálogo único la lectura cambia: verificar en la PC. Misma red que los atlas/mapas visuales de BR, IT y FR.
- Kit contable en RO: Contador en Acción (1418159758044206) 2/18 y MARCO MEDIA (1350956431432254) 0/11 «7 caiete + 6 bonusuri», mismo molde que Kit Comptable FR; lotes de ≤ 4 días, re-medir en 5 días.
- Diagram Books (1499263639932513) 0/30 y Neuralforkids (1336343509566915) 0/46 / Digital Books (1460770633775833) 0/20 con el mismo creativo «⭐ 4,9/5,0»: tandas de hoy, re-medir ~2026-11-20.
- Nota Maximă (147891488418749) ~25/48 en RON, pero libros escolares físicos («Asigurare Colet»): no entra.

RO 2026-11-15: domingo, lint de la cola; sin nodos, operadores ni agenda RO vencidos; nada que pase la vara.
RO 2026-11-15 (tarde): domingo, lint de la cola; sin nodos, operadores ni agenda RO; nada que pase la vara.

<!-- TARJETAS-MX: la sesión MX inserta sus tarjetas del día justo debajo de esta línea -->

### 🎯 Planeaciones y material para docentes (desde $99 MXN/mes) — Editorial MD MX · `material-docentes-planeaciones-mx` · 2026-11-17 · sesión MX
- **Qué es:** biblioteca digital editable (Word/PDF) de planeaciones didácticas, cuadernillos, listas de cotejo y carpeta CTE para maestros de preescolar a telesecundaria, «desde $99 al mes» / membresía VIP; también abre marketplace («vende tu material y gana 60 %»).
- **Por qué es ganador:** 14 de 14 ads activos en MX con 7+ días, un solo page_id; 10+ fechas de creación del 10-20 al 11-11, longevidad máx. ≈ 28 d, ad creado hace ~8 d; copy «la planeación que usan +3,800 maestras»; página sin cara ni marca personal.
- **Qué hacer:** llevar el molde «planeaciones listas por grado y mes + membresía» a BR (planejamentos BNCC para professores), PT, IT (programmazioni per docenti) y FR; en RO ya hay red de plantillas para profesores (Edulabs). Ojo: es suscripción y depende del currículo SEP; modelar como pack por grado con ticket único.
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=MX&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=328781457261320>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=28902328189398643
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-mx-B-huellas-nuevas-tarde.md`

### 🎯 Cuadernillo infantil personalizado con su nombre ($99-149 MXN) — Axo y Yo MX · `cuadernillo-personalizado-ninos-mx` · 2026-11-17 · sesión MX
- **Qué es:** cuadernillo de repaso por grado (kínder a 6°) con el nombre del niño («98 hojas con su nombre», tabla del 9 con las manos), $149 MXN (kínder $99); no se sabe si es PDF o impreso.
- **Por qué es ganador:** 12 de 26 ads activos en MX con 7+ días, un solo page_id y una sola oferta declinada por grado; 10+ fechas de creación, longevidad máx. ≈ 12 d y 14 ads nuevos <7 d (escalando); sin cara en los títulos.
- **Qué hacer:** modelar el molde «cuadernillo con el nombre de tu hijo» por grado en BR (caderno personalizado), PT, IT, FR y RO; ángulo: el niño es el protagonista. Verificar primero que sea entrega digital (si es impreso a domicilio, no entra).
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=MX&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1358953320636772>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (digital vs físico, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1117729777330281
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-17-mx-B-huellas-nuevas-tarde.md`

**Señales del día MX (tarde) 2026-11-17**
- Recursos Digitales Mx (758343707354463): 10/10 pero todos de ~70+ d y último ad creado ≈ 09-10: posible zombi, no pasa.
- Soluciones Educativas IA (709050228962169) 0/8 y Edugui Guías Educativas (907995442402809) 0/1: tandas de hoy; Alejandro Martínez (1461426360386692) «60 fichas visuales» de electrónica (BRL), ads de ~2 d: re-medir ~11-20.
- Nombres de docentes sin medir (1 ad en los 50): Planeaciones GM, Planeaciones Secundaria, Planeaciones Flor, Agenda del Profe.

MX 2026-11-17: nada que pase la vara; se midieron los 4 operadores MX por page_id (Enf. Valentina Rojas 2/16, Vida Práctica 0/6, 300 Mapas Mentales 18/24, Planner Hoy Solo 3 35/40). Informe: `RAW/cazas-auto/2026-11-17-mx-C-operadores.md`

**Señales del día MX 2026-11-17**
- Enf. Valentina Rojas (1419232917932388): 2/16; 8 ads de ~6-7 d cruzan 7 d entre hoy y 11-18 (llegaría a ~10); juzgar marca personal; re-medir ~11-19.
- Vida Práctica (1472534742604591): 0/6; techo 6, no llega a 10 salvo tandas nuevas.
- 300 Mapas Mentales 18/24 y Planner Hoy Solo 3 35/40: siguen vivos (tarjetas del 11-16).

### 🎯 +300 Mapas Mentales para Aprender Inglés — 300 Mapas Mentales MX · `mapas-visuales-mentales` · 2026-11-16 · sesión MX
- **Qué es:** kit digital de +300 mapas mentales de inglés (versión en español de la oferta de Fluente com Legenda, BR); precio no visto (cuenta en USD).
- **Por qué es ganador:** 20 de 28 ads activos en MX con 7+ días (11 con el título «+300 Mapas Mentales para Aprender Inglés»), un solo page_id y una sola oferta; 8 fechas de creación entre ~10-18 y 11-13, longevidad máx. ≈ 29 días; página sin marca personal.
- **Qué hacer:** llevar el molde «+300 mapas mentales de inglés» a otro idioma de destino: inglés para italianos, franceses y rumanos (y PT); BR ya lo corre Fluente com Legenda (tarjeta del 11-15). Ángulo: kit imprimible + bonos; el hueco en MX está ocupado (hay jugador).
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=MX&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1276104028925482>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1109796221531893
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-mx-A-huella.md`

### 🎯 Planner Hoy Solo 3 + 5 bonos de regalo — Planner Hoy Solo 3 MX · `planner-hoy-solo-3` · 2026-11-16 · sesión MX
- **Qué es:** planner imprimible de «3 prioridades del día» («Planner para vaciar la cabeza», «la lista eterna de tu cabeza cabe en una hoja») con 5 bonos; precio no visto (cuenta en USD).
- **Por qué es ganador:** 30 de 40 ads activos en MX con 7+ días (no truncado), un solo page_id y una sola oferta; 8+ fechas de creación, longevidad máx. ≈ 25 días, 4 ads nuevos de hace ~5 días; sin cara en los títulos.
- **Qué hacer:** modelar tal cual (planner de una hoja + bonos) en BR, PT, IT, FR y RO; evergreen, ángulo «vaciar la cabeza / elegir 3 de hoy».
- **Ads Library:** <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=MX&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1280820831792286>
- **Landing:** embudo no verificado desde la nube: verificar en la PC antes de decidir (tipo, precio, escalera n/e). Snapshot: https://www.facebook.com/ads/library/?id=1625984888978251
- Score n/4 (no evaluado) · Decisión: —
- Evidencia: API; snapshot y embudo no verificados desde la nube; longevidad por API, snapshot no verificado. Informe: `RAW/cazas-auto/2026-11-16-mx-A-huella.md`

**Señales del día MX 2026-11-16**
- Guías Técnicas Aprendia (1329947873543136): ≥12 verificados de ~80 (piso) en MX, «54 fichas / mapas mentales» repartido en ≥15 temas técnicos (ninguno ≥10); hermana Aprende Ya: Guías Aprendia (1288181344388955) ~120 ads en tandas de 1-6 d. Mismo molde multi-SKU que Studio Facile (RO); verificar en la PC si es catálogo único.
- Red «<tema> en Mapas» en MX, todas con tandas de hoy (0/6 c/u): Marta Aguirre Oratoria (1375259149015217, 60 mapas + 6 bonos), Aprenda Com Mapas (109742714002269), Isadora Martínez L. (1437086639485044), Central Criativa 4/8 (779654345226206); re-medir en 5 días.
- Lúmina: Digital Books & More (1272565179279345) 0/6 y Lo Quiero YA (1291890607347857) 1/6 / Digital By Dafne (1462894430233402) 1/4: «videos y PDF's», tandas chicas.
- Mujer con Valor (1369557812915882) 0/9: cuaderno de 62-110 páginas de ejercicios (autoestima), tanda de hace ~3 d; re-medir.

MX 2026-11-16 (tarde): nada que pase la vara; se barrió fichas anatomía, apuntes enfermería, fichas estudio pdf y 5 conteos por page_id (la mejor, Enf. Valentina Rojas 2/15). Informe: `RAW/cazas-auto/2026-11-16-mx-B-fichas-mapas-multitema-aprendia-tarde.md`

**Señales del día MX (tarde) 2026-11-16**
- Aprendia (Guías Técnicas 1329947873543136, Aprende Ya 1288181344388955, Paso a Paso 1381808071689792, Guías y Manuales 1300212443175450 + 4 hermanas): red de ≥ 8 fanpages con la plantilla «54 FICHAS PARA <tema>» en decenas de temas; los 50 ads más nuevos de cada página tienen ≤ 4 d, cohorte no medible (no es cero); fábrica de SKUs, no un SKU ganador; re-medir ~11-20.
- Enf. Valentina Rojas (1419232917932388): 2/15, «200 Mapas Mentales de Enfermería» a USD 3,99; 10 ads de ~6 d cruzan 7 d el 11-17/18 (llegaría a ~12); nombre de página = persona: juzgar marca personal en la PC; re-medir ~11-19.
- Atlas Visual Academy (1542154965638151) 0/5 «+250 fichas de Auxiliar de Enfermería» (EUR) y Ciencia Del Cuerpo (1231987839993612) 0/3 «+200 hojas de fisioterapia»: tandas de hoy.

MX 2026-11-16 (tarde 2): nada que pase la vara; se barrió cuaderno imprimible, plantillas excel, guía paso, pack editable, formatos listos, hojas trabajo y 10 conteos por page_id. Informe: `RAW/cazas-auto/2026-11-16-mx-B-huellas-nuevas-tarde2.md`

**Señales del día MX (tarde 2) 2026-11-16**
- Vida Práctica (1472534742604591): 0/12, «Manual Visual del Ingeniero Industrial / del Maestro de Obra» a $199 MXN; 3 ads de ~6 d cruzan 7 d el 11-17 (llegaría a 3); re-medir ~11-19.
- Tus Clases Online (103959345113295): 9/50 piso, multi-SKU (moldes navideños, cajitas, farmacología visual, mapas); los 9 con 7+ d son «Chatea con nosotros» genéricos, las ofertas reales tienen ≤ 6 d; el amigurumi cae en crochet (excluido); re-medir ~11-20.
- Estrategia Clara (1397477393443437) 4/13 («48 herramientas + 4 bonos», US$ 19,99, producto no identificado) y Kits Profesionales (692615883936217) 3/9 (kits documentales de salud/NOM en MXN): bajo la vara.
- Mente Ordenada (1084424138077543) 0/15 «vacía tu cabeza en 10 minutos», mismo ángulo que Planner Hoy Solo 3; tanda de hoy.

MX 2026-11-15: domingo, lint de la cola; sin nodos, operadores ni agenda MX vencidos; nada que pase la vara.

<!-- TARJETAS-CO: la sesión CO inserta sus tarjetas del día justo debajo de esta línea -->

CO 2026-11-17 (tarde): nada que pase la vara; se barrió guía pdf descarga inmediata, tarjetas estudio medicina, apuntes enfermería, apuntes veterinaria, resúmenes odontología pdf, plantillas psicología pdf (mejor: Cuaderno de Medicina - APP ≥50/160 activos, pero vende una APP y el embudo no se pudo verificar → no pasa el gate).

**Señales CO 2026-11-17 (tarde):** Cuaderno de Medicina - APP (1372929795909878) 160 activos en CO, ≥50 con 7+ d (piso), creativos «26 materias de Medicina», «¿Cuarenta PDFs sueltos?», «Recorre la app por dentro», «4.9/5», USD; parece app/suscripción de resúmenes, no PDF: verificar en la PC qué vende y a qué precio antes de decidir. Vetsemestresse 2/5 («Anatomía Vet para Colorear», ads de hoy). NeuroBits (flashcards inglés médico) 0/2.

CO 2026-11-17: nada que pase la vara; se barrió guía pdf acceso inmediato, plantillas excel editables, cuadernillo imprimible, kit digital COP, planner imprimible, guía práctica descarga inmediata, megapack pdf, formatos SG-SST (mejor: Gestión Profesional con Excel 5/7; Atril Estudio 0/50 piso, operador nuevo).

**Señales CO 2026-11-17:** Atril Estudio (1282575998279080) 0/50 piso, ads de 2-4 d, re-medir ~11-21. Gestión Profesional con Excel (961233043748737) 5/7. Digital Markett 3/7, Growing 3/14 (servicio contable mezclado).

**CO 2026-11-16 (tarde) · Pack de +2.000 partituras para piano/teclado — Rafael Piano Fácil** · `sin-revisar`
- Qué es: pack digital de «+2.000 Partituras para Piano/Teclado» (el segundo gancho: «Toque Piano/Teclado em 7 Dias»). Precio no visible por API; ads en USD. Nombre de página con nombre propio («Rafael»), pero los títulos venden el pack, no una cara: verificar en la PC.
- Por qué es ganador: cohorte 29/42 en CO (exacto, 42 < 50) de un solo page_id (p. 1109073548949200); 9 tandas de creación distintas (≈10-11 oct a hoy), ad más viejo ~34 d, 10 ads nuevos de hoy = operador vivo. El mismo operador corre la misma oferta en BR (≥50, en portugués) y en IT (≥49, «+1.000 Spartiti per Pianoforte/Tastiera»), señal de molde probado en 3 idiomas.
- Qué hacer: modelar tal cual (pack de partituras por nivel/género + guía de 7 días) · destino sugerido: FR o RO (en BR e IT el mismo operador ya está; en PT/FR/RO no se vio en los primeros 50, sin medir a fondo) · ángulo «+2.000 partituras, empezá hoy».
- Ads Library CO: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=CO&view_all_page_id=1109073548949200
- Landing: no verificada (la API no trae URL); precio y tipo de embudo por confirmar en la PC.
- Evidencia: API; snapshot y embudo no verificados desde la nube. Longevidad por API (~34 d en el ad más viejo), snapshot no verificado.
- Score —/4 · escalera n/e · Decisión: —

**CO 2026-11-16 · Guías visuales de teoría musical (guitarra / teclado / bajo) — Acordes en Claro** · `sin-revisar`
- Qué es: guías en PDF de teoría musical «dibujada» en 3 SKUs (guitarra, teclado, bajo); en FR el mismo operador habla de «340 pages, 148 exercices corrigés». Precio no visible por API. Copy con voseo argentino, ads en USD: el operador parece venir de AR y corre también en CO.
- Por qué es ganador: cohorte 27/50 en CO (piso; est. 354 activos) de un solo page_id (p. 1205940002609789); por oferta: guitarra 16, teclado 11. Creación en ≥4 tandas (≈10-26 oct, 11-06/07, 11-12, 11-14/15) y 4 ads más viejos (~31 d) fuera de los 50; ad nuevo hoy = operador vivo. Corre también en FR.
- Qué hacer: modelar tal cual (cuaderno visual de teoría para un instrumento) · destino sugerido: IT o PT/BR (ya corre en FR, no entrar ahí a ciegas) · ángulo «teoría de guitarra, pero dibujada», un SKU por instrumento.
- Ads Library CO: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=CO&view_all_page_id=1205940002609789 · ads viejos: https://www.facebook.com/ads/library/?id=1173748248947176 · https://www.facebook.com/ads/library/?id=1151250634106441
- Landing: no verificada (la API no trae URL); precio y tipo de embudo por confirmar en la PC.
- Evidencia: API; snapshot y embudo no verificados desde la nube. Longevidad por API (≥9 d dentro de los 50; ~31 d según la búsqueda por keyword), snapshot no verificado.
- Score —/4 · escalera n/e · Decisión: —

**Señales del día CO 2026-11-16 (tarde)**
- Prisma Piano (p. 1437920272732095): 0/5, los 5 ads son de hoy («La teoría del piano, en colores», «Los 7 acordes, con una regla»): el mismo molde visual de Acordes en Claro llevado a piano; re-medir ~2026-11-21.
- Sofia Rivas (p. 1207708585751063): ≥25 ads con 7+ d (de 101 activos; 50 visibles) con el creativo «(4,8/5) ⭐» en USD, aparece en ukelele/batería; oferta no identificada y nombre de persona, patrón de reseñas: no es tarjeta; verificar en la PC.
- Academia Visual de la Voz (p. 104143501451584): 0/7 (BRL, «¡Solo por hoy!», canto); 2 ads cruzan 7 d en ~4 h, re-medir mañana.
- Tamas Bodzsar (p. 198569693331735): 0/9, «El Código Rítmico» y «Escribe melodías», cuenta HUF, tanda de hace 2 d, marca personal probable.
- Nico Violín (p. 1427782124115740): 3 ads de hace ~4 d, «29,90 USD pago único», cuenta EUR; Ana Julia Mello (Setlist Sax) 3 ads de hoy. Sin cohorte.

**Señales del día CO 2026-11-16 (mañana)**
- Formula dg (p. 1365224956675289): 10/42 pero mezcla manuales PDF de PLC, acústica, iluminación y recetas (excluido); ninguna oferta sola llega a 10, no es tarjeta.
- Learning Online (p. 1007333979127805, cierre WhatsApp «recibe todo primero, aporta después»): 5/13, oferta no identificada; re-medir.
- Paquete De Diseños (p. 107416171593294): 3/20 (plantillas de velas y moldes MDF); 6 ads más cruzan los 7 d en ~8 h, re-medir mañana.
- Universo Pestanas (p. 783046031564048): 6/6 «$7», material de extensiones de pestañas, producto no confirmado.
- Talleres Listos (p. 1423115024221032): 4/17, «+150 dinámicas grupales»; Valentina Ríos 3/10 («+3000 ya lo descargaron»); Central Criativa 4/10; Los Resúmenes 2/6.
- Lectoescritura ya (p. 1294940880380557): 0/50 piso (est. 85), gancho «RECÍBELO GRATIS» (lead magnet); Maestro del Temario 0/18 (CNSC 2027, tanda de hoy-ayer); Click Inteligente 0/5.
- Hueco mapas mentales en CO: operadores ya presentes (300 Mapas Mentales, Marta Aguirre Oratoria, Isadora Martínez, Aprenda Com Mapas, Visión de águila 0/2, Inglés Con Mucho Vocabulario 0/3), todos en tandas de <4 días: ninguno con cohorte.

---

## Revisiones

| Fecha | Tarjetas revisadas | `Idea` | `tirar` | `re-cazar` | `profundizar` | Tasa |
|---|---|---|---|---|---|---|
| | | | | | | |

> Tasa = `Idea` / revisadas. Por debajo de 20 % se sube la vara; por encima de 70 % se baja.

## Histórico (decididas)

| Fecha | Sesión | Producto | Decisión | A dónde fue |
|---|---|---|---|---|
| | | | | |
