# Caza automática — MX · B perforar · material-docentes-planeaciones-mx — 2026-11-21 (tarde)

Contexto: sábado tarde; todos los nodos MX tocados hace menos de 7 días → se perfora `material-docentes-planeaciones-mx` (tocado por última vez el 11-17, el más viejo sin re-medir) con keywords nuevas y se re-mide la red de mapas. Mercado `["MX"]`, rol fuente.

## Shortlist

### SuperEdu (page_id 1856954204328477) — pasa la vara
- Ads Library MX: <https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=MX&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1856954204328477>
- ACTIVE 27 (ALL 28; el ad inactivo es de 2022). **Cohorte 19 / 27** con 7+ días (edades 9,1 a 42,2 d), 12 fechas de creación distintas (10-10 … 11-20), 8 ads de ≤ 2,8 d (operador vivo, tanda nueva «Planeaciones de Diciembre»). Moneda MXN.
- Oferta (títulos): Planeaciones mensuales/trimestrales de preescolar y primaria alineadas a la SEP («Planeación del Trimestre II para Primaria, de 1° a 6°», «Planeaciones de Diciembre para Preescolar»), Programa Analítico (preescolar y primaria, «DESCARGA», «EDITABLE»), Exámenes del Trimestre I, Reporte/Evaluación del Primer Momento, Plan Analítico + PMC. Multi-SKU por periodo escolar y nivel, entrega descargable.
- Sin persona/cara en los títulos; nombre de página de marca (SuperEdu). No marca personal.
- Precio: no visible en la API. Embudo: no verificado (la API no trae URL; snapshots dan 403 desde la nube).
- Flags: SKU atados al calendario SEP mexicano (se renuevan por trimestre/mes: hay que re-modelar por país); competidor del mismo nodo: Editorial MD (ya con tarjeta, suscripción $99/mes).

## Señales / descartes
- Guía del docente (1026455254031291): 4/8 (kits $249 MXN antes $359, por trimestre, preescolar/primaria/secundaria + exámenes); < 10; re-medir ~11-27.
- MAETA Crea (1321999554322707): 11/15 con 7+ d (hasta 46,8 d) pero **ningún título de ad, oferta no identificada** (no pasa el gate); verificar en la PC. Sin tarjeta.
- Zeroediciones.com (247025560540404): 22/22 activos, 17 creados el 2025-09-23 (~14 meses, ads zombi-like) + 5 de oct 2026; último creado hace ~33,8 d → posible zombi (no ≥ 1 ad en 30 d); oferta no identificada.
- Energía Rentable (656438854200927): ≥ 40 ads «Comenta Yo Quiero y te envío el link», todos de una tanda de ~45 d (2 fechas de creación, ninguno en 30 d) → posible zombi; oferta no identificada.
- Cuaderno de Derecho (1426557477213473): ≥ 50 ads USD, todos ≤ 4 d, **app** («una app en vez de un PDF gigante», 16 materias): app, no PDF; sin cohorte.
- Materiales Miss Josyu (656201290902349): 3/5 ACTIVE (≥ 7 d: 4 de 5), < 10. CEAA 3/7. Miss Criss de Hediec Digital 3 ads. Mente Viva (diagramas eléctricos, USD) 2 ads, 1 de ~11 d.
- Mapas oratoria (red-x-en-mapas-mx, Marta Aguirre Oratoria): keyword `mapas mentales oratoria` = 0 en ACTIVE; red sin re-medir con page_ids (sin ids a mano).

## Veredicto provisorio
ENTRAR (candidato) → destino sugerido: **FR / IT / RO / BR-PT** con planificaciones/programaciones por periodo para docentes (ya hay moldes hermanos: Pretty Little Teacher FR, L'angolo del Docente IT, Edulabs RO). MX es fuente. Observar: precio y formato por verificar en la PC.

## Cobertura
| Keyword | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| planeación didáctica | MX | 70 est. (50 devueltos) | — | SuperEdu, Guía del docente, Editorial MD, MAETA, muchos «Miss/Mtra» con 1-3 ads |
| manual visual electricista | MX | 51 est. | — | Energía Rentable (zombi), Mente Viva 2 ads, Ing Juan Carlos Pérez BRL |
| mapas mentales derecho | MX | 77 est. | — | Cuaderno de Derecho = app (USD, ≤ 4 d); ruido guitarra/tarot |
| cuadernillo preescolar | MX | 66 est. | — | Axo y Yo, MAETA, Guía del docente, Zeroediciones, Miss Josyu |
| programa analítico primaria | MX | 38 est. | — | SuperEdu, Guía del docente, Zeroediciones, Biblioteca Digital PRO |
| examen trimestre secundaria | MX | 8 est. | — | Klikka 2 ads, Guía del docente |
| mapas mentales oratoria | MX | 0 | no corrido | — |
| page_ids: Guía del docente, SuperEdu (ACTIVE y ALL), MAETA Crea, Zeroediciones, CEAA, Materiales Miss Josyu | MX | 8 / 27 / 15 / 22 / 7 / 5 | 28 (SuperEdu) | ver arriba |

Trampas nuevas: `manual visual electricista` en MX trae una tanda de 40 ads de «Comenta Yo Quiero» (Energía Rentable) que no es manual; la API no trae el cuerpo del ad, sólo el título → para ofertas de títulos vacíos (MAETA, Zeroediciones) la oferta queda no identificada.
Nodos nuevos propuestos para la cola: ninguno (SuperEdu va bajo `material-docentes-planeaciones-mx`).

## Lo que no se pudo verificar
Embudo/precio/formato de SuperEdu (API sin URL; snapshot 403); oferta de MAETA Crea y Zeroediciones; re-medición con page_ids de la red de mapas MX (sin ids).
