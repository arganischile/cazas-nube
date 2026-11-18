# RO 2026-11-18 (mañana) — modo C operadores

Evidencia: API (`ads_library_search`, `page_ids` + `countries: ["RO"]`, ACTIVE, limit 50); snapshot y embudo no verificados desde la nube (la API no trae URL de landing). Cohorte = `ad_creation_time` ≤ hoy−7 d (corte 1794390350).

## Conteos (cohorte / activos)
| Operador | page_id | Cohorte 7+ / activos | Lectura |
|---|---|---|---|
| Edulabs Resources | 1057793390758198 | 21 / 42 | 6 títulos en inglés (Theatre, Open.Print.Teach, Imagine, Financial Literacy) → 15 sin inglés; 9 con título rumano inequívoco (Religie ×6, Tot anul la primar ×2, Tot anul de română ×1), 6 sin título (probable rumano por lote). Multi-SKU, ningún SKU ≥10 (Religie 6). USD. Sin embudo verificado. Señal, no tarjeta: el conteo rumano verificado es 9 < 10 |
| Genius Mentor | 1202927619580444 | 3 / 50 piso (est. 95) | Solo los 3 «Ultima zi de Black Friday» (≈13 d) superan 7 d; los 40+ restantes son de 2-6 d. Cae vs 22/50 del 11-17 (se contó por inicio de entrega). Oferta de meditații/curso, no identificada |
| Rowan House Press | 103448682074390 | 5 / 44 | 5 ads de «Pâinea, cu desene» (~21 d); el resto, tanda del 11-16/17 (~1,5 d) de ~12 libros ilustrados, USD |
| Mesa Ligera | 1219245414615500 | 3 / 37 | EUR, multi-SKU; ningún SKU ≥10 (Un an la grădiniță ≈ 11 ads, todos de ≤ 7 d); los 3 con 7+ son sueltos |

No medidos por tiempo/presupuesto de contexto: Liveno (11-20), Ready Resources (11-20), Ioana Dumitrescu, Studio Facile.

## Cobertura
Modo C, tabla «Operadores a seguir» RO (Edulabs) + señales vencidas/cercanas del 11-16/17. Agenda de re-caza RO: vacía. Nadie pasa la vara → 0 tarjetas.
