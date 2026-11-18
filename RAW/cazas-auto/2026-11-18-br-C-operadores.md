# Caza automática — BR · C operadores · 2026-11-18 (mañana)

Evidencia: API (`ads_library_search`, `countries: ["BR"]`, ACTIVE, limit 50). Ahora = 2026-11-18 06:30 Santiago; cohorte = `ad_creation_time` hace 7+ días (≤ 2026-11-11 09:30 UTC) y todavía activo. Snapshot y embudo no verificados desde la nube.

## Shortlist
**Rafael Piano Fácil BR** (page_id 1109073548949200) — 31/50 piso (68 est. activos), ≥20 con título inequívoco en portugués («Piano e Teclado», «Toque … em 7 Dias»); tandas de creación 10-27, 10-28, 10-31, 11-06, 11-12, 11-16, 11-17; moneda USD. Misma oferta que tarjetas CO (11-16) e IT (11-17). Pasa la vara → tarjeta. Duda: nombre de pila en la página (juzgar en la PC).

## Veredicto provisorio
Observar/ENTRAR condicionado: molde «pack de partituras por instrumento» validado en BR + CO + IT por el mismo operador; llevar a PT y RO (FR sin medir). BR es el mercado de mayor volumen del operador (probable origen).

## Cobertura (conteos por page_id, BR, ACTIVE)
| Operador | page_id | Cohorte / activos | Nota |
|---|---|---|---|
| Tudo sobre unhas | 106958424923732 | 0 / 50 piso (92 est.) | 50 más nuevos de 11-15 a 11-18; SKUs: matemáticas 1º-5º, diagnóstico de motos, colorir, moldes, copos 360, treinos femininos, instrumentais, tabuada, desenvolvimento infantil (más SKUs de recetas: excluido, se ignora) |
| Mapas e Guias Visuais | 1394868680373327 | 6 / 6 | cayó de 127 est. a 6; un SKU USD «Teste antes de trocar a peça» |
| Riscos para Bordar | 396283016894466 | 0 / 4 | ads de 11-15, «4.9/5.0» |
| Guia dos Benefícios Sociais | 1415031105033080 | 7 / 7 | subió de 0/7; < 10, eje cerrado |
| Rafael Piano Fácil | 1109073548949200 | 31 / 50 piso (68 est.) | tarjeta |
| Camila Maia | 582679418253715 | 13 / 45 | estable, tarjeta del 11-17 |
| Edital Master | 125481670646964 | 12 / 50 piso (57 est.) | 16 el 11-17; la tanda del 11-10 (SESAB, Saquarema) cruza 7 d hoy-mañana |
| Fluente com Legenda (USD) | 837003542818622 | ≥22 / 50 piso (236 est.) | tarjeta vigente (local) |
| Fluente com Legenda (BRL) | 996556976874285 | 0 / 2 | |
| Academia da legenda | 1521661844353417 | 0 / 7 | clon nuevo, ads 11-16/17, «4,9/5» |
| Nannyvarie | 101372751885586 | 39 / 46 | estable, tarjeta vigente |
| Organize com Ju | 1022767074413574 | 11 / 16 | tarjeta vigente; «curso de dobras com Ju Saippa» → posible marca personal |
| Maria Eduarda | 1389112280954409 | 0 / 6 | apagó la tanda vieja, todo de hoy |
| Ryu Nakamura | 1237334109469401 | no medible (1.229 est.; 20 visibles de ≤ 2 d) | marca personal; agenda 11-24 es del dueño |

Keywords corridas: ninguna de descubrimiento (modo C); 3 búsquedas por nombre de página (fluente legenda mapas, nannyvarie, organize com ju, kit corredores) para recuperar page_ids.
Trampas nuevas: `fluente legenda mapas` devuelve 3 páginas distintas con el mismo nombre (996556976874285 BRL, 837003542818622 USD y Academia da legenda); contar cada page_id por separado.
Nodos nuevos propuestos: ninguno.

## Lo que no se pudo verificar
Embudo, precio y tipo de página de todos (landings sin URL en la API; snapshots 403 desde la nube). Si «Rafael» es cara o nombre de marca.
