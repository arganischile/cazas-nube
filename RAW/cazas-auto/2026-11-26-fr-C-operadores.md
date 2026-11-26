# Caza automática — FR · C operadores · operadores FR vencidos/de la semana + agenda — 2026-11-26

Corrida de la mañana (jue → C operadores). Hora de corte: 2026-11-26 ~09:42 UTC (06:42 America/Santiago).
Cohorte = ads activos en FR con `ad_creation_time` ≥ 7 d. Evidencia solo por API (`ads_library_search`,
`page_ids` + `countries: ["FR"]`, `limit: 50` = piso); snapshots y embudos no verificados desde la nube.

## Shortlist

### 1. Mémofiches (page_id 1464062913449663) — fábrica de fiches visuelles de révision por concurso/examen
- Ads Library FR: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&view_all_page_id=1464062913449663&search_type=page&media_type=all
- ACTIVE FR: **11/11** con 7+ d (no truncado): 7 × «120 fiches pour le concours de policier» (creados 2026-11-19 09:21 UTC, 7,0 d: cruzaron los 7 d esta mañana) + 4 × «36 fiches visuelles d'anesthésie» (2026-11-11, 14,4 d).
- ALL FR: 29 → SKUs: concours policier 120 fiches, Concours Adjoint Administratif 60 fiches (4, 11-19, apagados), DroitFiches 80 fiches de droit L1-L2 (4, 11-19, apagados), Brevet maths 5 sujets blancs corrigés (4, 11-13), planner d'études avec stickers d'anatomie (11-13), «Apprends à retenir» (10-31), anesthésie (11-11).
- Fechas de creación: 10-31, 11-11, 11-13, 11-19 (operador vivo, ≥ 3 fechas, último ad < 30 d). Moneda USD (operador extranjero corriendo FR). Página genérica, sin persona.
- Lectura: testea un SKU por semana y deja vivo lo que convierte; policía y anestesia sobreviven, adjoint administratif y droit se apagaron en < 7 d.
- IT/PT/BR/RO: 0 activos de esta página.
- Hooks: «Oubliez les PDF de 1 000 pages», «Un thème par page, tout est clair», «120 fiches, toujours le même modèle», «Les curares, enfin clairs».
- Snapshots: 2064397634053988 · 1677372217244621 · 1734548168679606.
- Flags: cohorte justa (11) y 7 de los 11 cruzaron los 7 d hace horas; multi-SKU (por oferta: policía 7, anestesia 4). Embudo y precio no vistos.
- Score provisorio 1/4 (escalonamiento y molde repetible; embudo, precio y duplicación fuerte sin ver).

### 2. Mission parent (page_id 994644443736564) — «système» de routines/autonomía para niños
- Ads Library FR: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=FR&view_all_page_id=994644443736564&search_type=page&media_type=all
- ACTIVE FR: **20/28** con 7+ d (no truncado). Tandas: 10-22 ×4, 10-31 ×3, 11-17 ×13, 11-22 ×8. Ad más viejo ≈ 34,7 d. Moneda EUR. Subió de 8/30 (11-24).
- Títulos: «Des repères pour un quotidien plus apaisé» (×15), «Un système qui change tout» (×6), «La maison tourne sans moi et je respire enfin.» (×5), «Un cadeau pour son autonomie 💛», «Black Friday : un cadeau qui fait grandir».
- Nombre de página genérico, sin persona.
- ⚠️ «cadeau» + «Black Friday» sugieren objeto físico (tablero de autonomía / routine chart); la sesión del 11-24 ya lo había marcado «probable físico». El dolor (rutinas, autonomía, carga mental del padre) se resuelve con conocimiento + imprimibles → pasa como «FÍSICO: pasarlo a digital».
- IT/PT/BR/RO: 2 activos (los mismos creativos en francés; no hay SKU local).
- Snapshots: 2177580232969411 · 1852040875789898 · 1454800836810871.
- Score provisorio 1/4 (duplicación ×15 del mismo título y escalonamiento; embudo, formato y precio sin ver).

## Veredicto provisorio
- Mémofiches → ENTRAR (modelar molde «fiches visuelles por concurso/profesión») → destinos IT (concorsi: ya hay mercado de mappe per concorsi), PT/BR (concursos), RO. Verificar embudo y precio en la PC.
- Mission parent → observar / ENTRAR si el embudo confirma que se puede vender como PDF imprimible (routines + tablero de autonomía imprimible) → destinos IT, PT/BR, RO.
- Nunca DESCARTAR.

## Operadores re-medidos (FR, ACTIVE, cohorte 7+ / activos)

| Operador | page_id | Hoy | Antes | Nota |
|---|---|---|---|---|
| Mémofiches | 1464062913449663 | 11/11 | 4/11 (11-23) | tarjeta |
| Mission parent | 994644443736564 | 20/28 | 8/30 (11-24) | tarjeta |
| Kaito Vale | 1141489242390653 | 34/34 | 34 (11-23) | títulos vacíos, oferta no identificada (WebSearch sin resultado); tandas 10-19, 11-06, 11-11, 11-13; sin ad nuevo en 13 d; nombre de persona (¿coach ficticio de la red Calistenia Asiática?) → no se puede pasar el gate desde la nube |
| Pretty Little Teacher | 398932843295914 | 34/50 piso (75 est.) | 36/46 (11-20) | ya con tarjeta; tandas nuevas 11-24/25 ×16 (promo fin de año / Black Friday) |
| Esprit Académique | 1229441186928180 | 47/50 piso (101 est.) | ≥50/95 (11-18) | ya con tarjeta; **SKU nuevo** «+300 Cartes Mentales pour Apprendre l'Espagnol» (3 ads, 11-25) |
| Fenix Library | 1455853117614278 | 0/50 piso (79 est.) | 0/50 (11-24) | rota todo: los visibles son 11-23→11-25; SKUs nuevos QualiPAC, frigoriste, production musicale; las tandas del 11-19 ya no aparecen |
| Inspiracion Studio (Cricut) | 1096725376864125 | 4/10 | 4/11 (11-23) | estable, sin cohorte |
| Hugo Jean | 1382251738298675 | 5/15 | 0/11 (11-23) | «Une fiche. Une aventure. Un souvenir.» 5/5 (11-18); «14 jours… coups de pied» 0/10 (11-23/24) |
| Le Kit Vagal | 1301216783083922 | 6/10 | 6/17 (11-23) | «64 cartes du nerf vague + 200 fiches» (USD), tanda nueva 11-23 ×4 |

No re-medidos hoy (agenda ~11-30, ya con tarjeta o apagados): Amélie Boissieu, PsiOS, Car Station, Biblioteca Práctica, La Bible sur papier, Espagnol Illustré, Sunday Budget, Bibliothèque Créative, La fée du budget, FocusDaily, Make you Happy, Lumen Arte.

Agenda del hub: Calistenia Asiática (vencida 11-24) — la parte FR es Kaito Vale (medida arriba, 34/34 sin oferta identificable desde la nube). Pflegelernzettel (12-19) no vence esta semana.

## Cobertura
| Keyword / consulta | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| page_id Mémofiches | FR | 11 | 29 | 11/11; multi-SKU |
| page_id Mémofiches | IT/PT/BR/RO | 0 | — | sin presencia |
| page_id Fenix Library | FR | 79 est. (50) | — | 0/50 piso |
| page_id Inspiracion Studio | FR | 10 | — | 4/10 |
| page_id Hugo Jean | FR | 15 | — | 5/15 |
| page_id Esprit Académique | FR | 101 est. (50) | — | 47/50 piso, SKU nuevo |
| page_id Mission parent | FR | 28 | — | 20/28 |
| page_id Mission parent | IT/PT/BR/RO | 2 | — | creativos en francés |
| page_id Le Kit Vagal | FR | 10 | — | 6/10 |
| page_id Kaito Vale | FR | 34 | — | 34/34 sin títulos |
| page_id Pretty Little Teacher | FR | 75 est. (50) | — | 34/50 piso |
| WebSearch «Mission parent», «Kaito Vale», «Mémofiches» | — | — | — | nada útil |

Trampas nuevas: ninguna. Nodos nuevos propuestos: `fiches-concours-memofiches-fr` (virgen), `routines-autonomie-enfant-mission-parent-fr` (virgen).

## Lo que no se pudo verificar
- Embudos y precios de Mémofiches y Mission parent (la API no trae URL de landing; snapshots 403 desde la nube).
- Si Mission parent vende objeto físico o PDF.
- La oferta de Kaito Vale (títulos vacíos).
