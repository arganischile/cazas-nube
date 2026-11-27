# Caza automática — MX · C operadores · — — 2026-11-27 (mañana)

Evidencia: API (`ads_library_search`, `countries: ["MX"]`, ACTIVE, `limit: 50`); snapshot y embudo no verificados desde la nube. Cohorte = ads creados hace 7+ días y activos (corte 2026-11-20), `cohorte / activos`.

## Shortlist
Ninguna tarjeta nueva. Todas las ofertas con cohorte ≥ 10 ya tienen tarjeta en la bandeja (van como señal) y no apareció SKU nuevo con cohorte propia.

| Operador | page_id | Cohorte 7+ / activos (MX) | Cambio vs última medición |
|---|---|---|---|
| Mente Académica (`mapas mentales` + page_id) | 1239880759219492 | ≥ 50/50 piso (164 est.; BRL; «+300 Mapas Mentales de TI» 13 ads de 10,7 d, «200 Mapas Mentales de Ing. Civil» 37 ads de 14-15 d) | estable, ya con tarjeta |
| Planner Hoy Solo 3 | 1280820831792286 | ≥ 43/50 piso (54 est.; USD; un solo SKU «Planner para vaciar la cabeza», 11 a 34 d) | creció (30/40 el 11-16); ya con tarjeta |
| Axo y Yo | 1358953320636772 | 21/26 (MXN $99-149; 5 ads nuevos de ≤ 2,7 d; máx. 21,5 d) | creció (15/22 el 11-20); ya con tarjeta |
| Mapas Visuales PRO | 1291088710759821 | 17/31 (PEN; Megapack Automatización Industrial, Ing. Civil, «usa mapas visuales»; máx. 70 d; lote de inglés de ≈ 2 d: 9 ads) | 17/31 vs 20/36 el 11-26 (algunos ads se apagaron); ya con tarjeta |
| Psicologia & Recursos 2025 | 469568772899568 | 16/16 (COP; 10 ads de 17,3 d: KIT Terapia de pareja, Duelo, Orientación vocacional, Trabajo social; 6 de 46-48 d) | igual (16/16); ya con tarjeta |
| Editorial MD | 328781457261320 | 7/10 | bajó (14/14 el 11-17); un ad de hoy «Cuaderno docente CTE … MEMBRESÍA VIP» (multi-título) |
| 300 Mapas Mentales | 1276104028925482 | 4/9 (USD; «+300 Mapas Mentales para Aprender Inglés») | bajó (20/28 el 11-16): la tanda se apagó, quedan 3 ads de hoy |
| Vida Práctica | 1472534742604591 | 2/4 (MXN $199, «Manual Visual del Ingeniero Industrial», 2 de 16 d y 2 de 1,2 d) | bajó (3/3) |
| Atril Estudio | 1282575998279080 | 0/50 piso (261 est.; USD; «⭐ 4.9/5 Estrellas» + «Aprende a soldar en casa»; todo ≤ 2,7 d) | tandas diarias: cohorte no medible, sigue sin producto identificable por API |
| Tus Clases Online | 103959345113295 | 0/50 piso (202 est.; MXN/USD; ≤ 2,6 d; navidad, mascotas, bebés, regalos, «Véndelas en $300–500», adviento $69) | multi-SKU en tandas diarias; no medible hoy |

## Veredicto provisorio
Nada nuevo para decidir. Observar: Atril Estudio (≥ 261 est.; verificar en la PC qué vende, es la mayor cohorte potencial del eje) y Tus Clases Online (re-medir ~12-01 con `search_terms` por SKU + `page_ids`).

## Cobertura
| Keyword / consulta | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| page_ids Vida Práctica | MX | 4 | — | 2/4 |
| page_ids Axo y Yo | MX | 26 | — | 21/26 |
| page_ids Psicologia & Recursos 2025 | MX | 16 | — | 16/16 |
| page_ids Atril Estudio | MX | 50 (piso, 261 est.) | — | 0/50 |
| page_ids Mapas Visuales PRO | MX | 31 | — | 17/31 |
| page_ids 300 Mapas Mentales | MX | 9 | — | 4/9 |
| page_ids Planner Hoy Solo 3 | MX | 50 (piso, 54 est.) | — | ≥ 43/50 |
| page_ids Editorial MD | MX | 10 | — | 7/10 |
| `mapas mentales` + page_ids Mente Académica | MX | 50 (piso, 164 est.) | — | ≥ 50/50 |
| page_ids Tus Clases Online | MX | 50 (piso, 202 est.) | — | 0/50 |

Trampas nuevas: en páginas con tandas diarias (Atril Estudio, Tus Clases Online) los 50 más nuevos tapan lo viejo; contar con `search_terms` por SKU + `page_ids`. Planner Hoy Solo 3 y Mente Académica también topan el piso de 50.
Nodos nuevos propuestos para la cola: ninguno.

## Lo que no se pudo verificar
Embudo y precio de todos (snapshot y landing no abiertos desde la nube); qué vende Atril Estudio (el copy no trae producto por API); Psicologia & Recursos hermana 163465520189615 y Aula Creativa Inicial no se re-midieron hoy.
