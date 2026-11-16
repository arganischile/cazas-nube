# Caza automática — RO · A huella · — — 2026-11-16 (mañana)

Modo: lunes = A huella (columna RO de la rotación). Mercado `countries: ["RO"]`, rol destino y fuente.
Corte de cohorte: ads con `ad_creation_time` anterior a ~2026-11-09 09:45 (hace 7+ días). Longevidad y zombis por API (NUBE.md §4). Snapshots y embudos no verificados desde la nube (la API no trae URL ni cuerpo).

## Keywords corridas (nativas, ACTIVE, limit 50)
`ghid pdf` (est. 124) · `acces imediat` (703) · `planner imprimabil` (0) · `fișe imprimabile` (6) · `ebook complet` (114) · `caiet exerciții` (72) · `șabloane gata` (30) · `descarcă ghidul` (267).
Basura: `ebook complet` = editoriales y libros de ficción (Corola, Editura ACT), `descarcă ghidul` = lead magnets gratis de clínicas/ONG/ROCKWOOL, `acces imediat` = hoteles y tandas de hoy de páginas cáscara en USD. `planner imprimabil` da 0 (con ACTIVE; no se repitió con ALL: queda como hueco no confirmado).

## Conteos por page_id (cohorte 7+ / activos; piso = 50 devueltos)
| Página | page_id | Cohorte / activos | Qué es |
|---|---|---|---|
| Studio Facile (A) | 1272162682644374 | ≥17 / 54 (piso) | «X în imagini»: libros visuales por tema (Electronica 6, PLC 6, Ventilația 5…). Ningún tema ≥10 |
| Studio Facile (B) | 1232011766670582 | 38 / 48 | misma marca, otra página, ~20 temas (Sudura 5, Contabilitatea 5, Teoria muzicii 5…). Ningún tema ≥10 |
| Nota Maximă | 147891488418749 | ~25 / 48 | libros escolares (clasa IV-VIII, Evaluare, Bac), copy «Asigurare Colet» → producto físico: no entra |
| Neuralforkids | 1336343509566915 | 0 / 46 | creativo «⭐ 4,9/5,0» en USD; el más viejo de ~6,6 d → re-medir ~11-20 |
| Digital Books | 1460770633775833 | 0 / 20 | mismo creativo «⭐ 4,9/5,0»; el más viejo de ~2,6 d |
| Diagram Books | 1499263639932513 | 0 / 30 | «+ 2 cărți cadou» (Altoirea, Porcul acasă, PSI…), tandas de 2-4 d |
| Contador en Acción | 1418159758044206 | 2 / 18 | «6 caiete de contabilitate practică», 3 lotes de hoy, ya 1 a 30 d |
| MARCO MEDIA | 1350956431432254 | 0 / 11 | «Antrenament contabil 2027 · 7 caiete + 6 bonusuri» = Kit Comptable de FR en rumano |
| Harta Tulburărilor | 1385099554683635 | 1 / 23 | «210 fișe, 40 de perechi, 1 PDF» (EUR), tandas de hace 1-5 d |
| Skillnest | 1349147928291623 | 0 / 5 | desenul técnico/H7, «Ghid + 3 bonusuri, în PDF» |
| Imago Studiu | 1324183297455293 | 5 / 5 | «Tăierea pomilor + 2 cărți cadou», ~11 d |
| Salud Didáctica | 1060368773817749 | 0 / 10 | manuales médicos (perfuzii), ~4,5 d |
| Gabriele Bianchi | 1502173249635679 | 0 / 5 | «140+ exerciții la radiografie», nombre de persona, de hoy |
| Pixpixels Edu | 772797809259875 | 1 / 1 | caiete educaționale PDF, RON, 1 ad |

## Veredicto
Ninguna página pasa la vara (10+ ads con 7+ días en una sola oferta). **0 tarjetas.**
- Studio Facile es el caso más cercano: 17+ y 38 ads viejos entre dos páginas, pero repartidos en ~20 temas; ningún tema pasa de 6. Si la oferta real es un catálogo/bundle («Răsfoiește înainte să descarci» es el hook genérico), la lectura cambia: verificar en la PC. Es la versión RO de la red de libros visuales (BR Mapas e Guias Visuais, IT learndigital.shop «Atlas Vizual», FR Bibliothèque Créative).
- Kit contable: la misma oferta aparece en FR (Amélie Boissieu ≥32/50), y en RO por dos páginas (Contador en Acción, MARCO MEDIA) lanzadas hace ≤ 4 días. Señal de que el molde se está llevando a RO: re-medir en 5 días.
- Nota Maximă es el único operador con RON y cohorte grande, pero vende libros físicos: no se trae.

## Cobertura
8 keywords nativas, 14 conteos por page_id. No se declara el mercado vacío: barrido superficial; los nodos vuelven a la cola. `ad_active_status: ALL` solo no se corrió para `planner imprimabil` (0): pendiente.
