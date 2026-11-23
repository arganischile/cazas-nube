# Caza FR · 2026-11-23 (tarde) · B perforar · jeux-dynamiques-300-pret-a-utiliser

Corrida de nube, sin navegador. Evidencia: API `ads_library_search` (countries FR). Ahora = 2026-11-23 ~18:40 America/Santiago (epoch 1795470086); cohorte = activos con `ad_delivery_start_time` ≤ 1794865286 (7+ d).

## Elección del nodo
Todos los nodos FR fueron tocados en < 7 días; se toma el virgen más viejo nunca perforado en modo B: `jeux-dynamiques-300-pret-a-utiliser` (huella 11-16). Pendiente del nodo: identificar el público (riesgo de adultos mayores, excluido).

## Re-medición del operador de origen
- **Hugo Jean** (p. 1382251738298675): **0/12** activos en FR (ALL est. 261). La oferta «300 jeux & dynamiques prêts à utiliser 🏃» ya no tiene ads activos (tandas 10-31 a 11-11 apagadas). Activos: «14 jours pour l'amplitude de tes coups de pied» ×7 (de hoy) y «Une fiche. Une aventure. Un souvenir.» ×5 (11-18, ≈ 5,5 d). BRL.
- **Público resuelto por los títulos de ALL:** «300 fiches de training fonctionnel prêtes», «Tes élèves devinent déjà l'exercice ?», «Ta séance prête en 2 minutes», «Plus d'idées pour varier tes séances ?», «300 dynamiques, rangées en 7 catégories» → **entrenadores / coaches deportivos y profes de EPS**, no adultos mayores. El riesgo de exclusión del nodo se levanta (con la reserva de verificar en la PC).

## Keywords nativas (subagente de solo lectura, countries FR)
| keyword | estado | total est. | páginas relevantes |
|---|---|---|---|
| fiches séances EPS | ACTIVE 0 → ALL | 12 | Hugo Jean (5, apagados), APSA Fiches (4, apagada), Orbis Atlas «10 tomes EPS» (1), Digital Premium (1), supermaitresse.sylviehanot (marca personal) |
| jeux sportifs enfants fiches | ACTIVE 0 → ALL | 11 | Hugo Jean (8, «300 jeux»), Ceméa France (coffret físico) |
| séances entraînement football pdf | ACTIVE 0 → ALL | 19 | Coachai Pro y Lucas Benett (apps IA), L'Atelier Pratique 2, Mr Coach «Coach's Vault Football» 2, EuroHacks 1 — todos apagados |
| fiches exercices prêtes à utiliser | ACTIVE | 16 | **EDT Labs 8**, Le Kit Vagal 4, NeuroKit Clínico 2, Evolui mais 1 («La boîte à outils du coach — 13,90 €») |
| jeux de cohésion animation | ACTIVE | 4 | ninguna (team building/eventos) |
| programme entraînement pdf coach | ACTIVE | 10 | Coach's Fitness Challenge 6 (reto fitness B2C, EN/ES/FR), apps (WellMate, 7Running) |
| jeux d'animation colonie | ACTIVE | 272 | ruido (escuelas, eventos, turismo; una residencia senior → excluido, ignorado) |

## Conteo por page_id (FR, ACTIVE)
| página | page_id | cohorte/activos | fechas creación | ≥1 en 30 d | moneda | qué vende | flags |
|---|---|---|---|---|---|---|---|
| **EDT Labs** | 1377084598812432 | **18/27** (no truncado) | 3 (11-11 ×10, 11-13 ×8, 11-19 ×9) | sí | USD | «Vos cours de maths déjà prêts» / «Maths Prêtes™» / «Retrouvez vos dimanches soirs» | verificado por mí; ad activo más viejo 11-11 (≈ 12,5 d) |
| Le Kit Vagal | 1301216783083922 | 6/17 | 3 | sí | USD | «64 cartes du nerf vague + 200 fiches», «MassoFiches 70 manœuvres» | ¿físico o PDF? |
| Hugo Jean | 1382251738298675 | 0/12 | 2 | sí | BRL | SKU nuevos (coups de pied, fiche aventure) | oferta de referencia apagada |
| Digital Premium | 1194310883757862 | 0/18 | 4 | sí | USD | tienda multi-SKU de fichas (auto, foto, yoga) | — |
| Coach's Fitness Challenge | 1100533076468908 | sin calcular (198 est., FR 6) | — | sí | USD | reto fitness consumidor final | no es pack para coaches |
| APSA Fiches, Orbis Atlas, Mr Coach, L'Atelier Pratique, EuroHacks | — | 0 activos | — | — | — | packs EPS/fútbol | apagados |

## Gate de EDT Labs
- Marca personal: no (nombre de marca, títulos sin cara/persona).
- Producto: «cours de maths déjà prêts» = clases/secuencias de matemáticas listas para profesores (digital por la forma, a verificar). Nicho no excluido.
- Zombi: no (3 fechas distintas, tanda nueva hace ~4,5 d).
- Embudo: la API no devolvió bodies ni URL → no verificado desde la nube. Precio no visto.
- Evolución: 4/8 el 11-21 (señal en `manuels-illustres-concours-fr`) → 18/27 hoy. Cohorte joven (≈ 8-12,5 d): dos tandas, no longevidad larga.
- Ligar con `ressources-enseignants-pretty-little-teacher-fr` (recursos docentes FR) y Belle Plume.

## Score
① longevidad 45+ no (≈ 12,5 d) · ② volumen 50+ no (27) · ③ duplicación: 3 títulos sobre una oferta, tandas de 8-10 ads → sí moderada · ④ hueco: sin medir en IT/RO/PT. Provisorio 1/4.

## Cobertura
- Nodo `jeux-dynamiques-300-pret-a-utiliser`: 7 keywords nativas (3 con ALL) + 2 conteos por page_id propios + 5 del subagente. Nadie del nicho deportivo/EPS con cohorte: el nicho está apagado en FR hoy (todas las ofertas EPS/fútbol vistas en ALL sin activos). **Barrido superficial**, no se declara vacío.
- No medido: IT/RO/PT para packs de entrenadores (`schede allenamento calcio pdf`, `fișe antrenament`), ni subnichos yoga/pilates para instructores.
- Trampas nuevas: `jeux d'animation colonie` (272) = ruido institucional; `séances entraînement football pdf` = apps IA de coaching; `programme entraînement pdf coach` = retos fitness B2C.

## Salida
1 tarjeta (EDT Labs 18/27). Señales: Hugo Jean 0/12 (oferta «300 jeux» apagada; público = coaches/EPS), Le Kit Vagal 6/17.
