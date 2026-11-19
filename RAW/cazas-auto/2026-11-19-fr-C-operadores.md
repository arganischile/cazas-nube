# Caza automática — FR · C operadores · (operadores FR + agenda) — 2026-11-19

## Shortlist
Ninguna tarjeta nueva. Todo operador FR con cohorte ≥ 10 ya tiene tarjeta pendiente en la bandeja (Boissieu, Espagnol Illustré, PsiOS, Car Station, Esprit Académique, La fée du budget, Hugo Jean): no se duplican, van como señal con la re-medición.

## Veredicto provisorio
observar. Sin SKU nuevo ni país nuevo en los operadores medidos.

## Cobertura (conteos por page_id + countries ["FR"], ACTIVE salvo nota; ahora = epoch 1795081000, cohorte = delivery_start ≤ 1794476200)
| Operador | page_id | est. | n | cohorte | edad máx/mín (d) | Nota |
|---|---|---|---|---|---|---|
| Amélie Boissieu (Kit Comptable 2027) | 1363004406903385 | 73 | 50 | 42 (piso) | — | un solo título «Kit Comptable Pratique 2027 · 7 cahiers + 6 bonus», USD; última creación hace ~0,2 d: sigue con tandas nuevas |
| Espagnol Illustré | 1435820002945205 | ACTIVE 0 / ALL 35 | 35 | 23 (ALL) | 19,4 / 1,8 | **ACTIVE devuelve 0**: posible apagado; estado por ad no visible con ALL; re-medir pronto |
| PsiOS | 111707335304926 | 37 | 37 | 24 | 56,4 / 1,7 | un producto multilingüe (DE/IT/FR/ES/EN), USD |
| Car Station | 1124004904129860 | 47 | 47 | 24 | 18,1 / 0,3 | 38 de 47 con el título «12 manuels + 5 outils pour l'atelier»; tanda nueva de 23 ads |
| Biblioteca Práctica | 1415895891603865 | 11 | 11 | 5 | 18,9 / 0,1 | COP/USD, 3 títulos |
| Esprit Académique | 1229441186928180 | 95 | 50 | 49 (piso) | 37,7 / 6,9 | BRL, sin tanda nueva desde 11-06 |
| Inspiracion Studio | 1096725376864125 | 10 | 10 | 8 | 34,1 / 1,1 | USD |
| La fée du budget | 387445394447918 | 23 | 23 | 23 | 18,4 / 9,5 | EUR, planner 37 € |
| Sunday Budget | 1378372592023348 | 5 | 5 | 2 | 12,2 / 2,1 | USD |
| Hugo Jean | 1382251738298675 | 32 | 32 | 27 | 48,2 / 0,9 | BRL, 300 jeux & dynamiques |
| Bibliothèque Créative | 1501332446389326 | 6 | 6 | 0 | 4,9 / 0 | BRL, tanda reciente |
| Pharmacologie Simplifiée (agenda DE→FR) | 1391162887408497 | 10 | 10 | 0 | ~2 d | «Top 200 des médicaments en images», 4,9/5, USD; todo creado 11-17 |
| L'Antisèche Infirmière (agenda DE→FR) | — | 0 | 0 | 0 | — | `Antisèche Infirmière` ACTIVE = 0 (no medido con ALL ni por page_id) |

Keywords corridas: ninguna (modo C). Subagente de solo lectura hizo los conteos de 10 operadores; Boissieu y la agenda los hice yo.
Trampas nuevas: con `ALL` el resultado no distingue activos de inactivos; Espagnol Illustré da ACTIVE 0 pero ALL 35.
Nodos nuevos propuestos para la cola: ninguno.

## Lo que no se pudo verificar
Embudos y snapshots (403 desde la nube). Estado de los 35 ads de Espagnol Illustré. Agenda Pflegelernzettel (DE) vence 11-21: destinos IT/PT sin medir hoy; en FR, Pharmacologie Simplifiée 0/10 (todo de 11-17) y L'Antisèche Infirmière sin ads activos.
