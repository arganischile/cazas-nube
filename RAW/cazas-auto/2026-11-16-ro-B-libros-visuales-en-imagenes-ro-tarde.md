# Caza automática — RO · B perforar · libros-visuales-en-imagenes-ro — 2026-11-16 (tarde)

Evidencia: solo API (`ads_library_search`, `countries: ["RO"]`); snapshot y embudo no verificados desde la nube (la API no trae URL de landing, WebFetch no aplica). Longevidad = hoy − `ad_delivery_start_time`. Cohorte = ads con inicio de entrega y creación ≥ 7 días atrás (corte ≈ 2026-11-09 18:45), reportada `cohorte / activos`, `limit: 50` = piso.

## Shortlist

### 1. Atlas Terapeutic Vizual — page_id 1408033785736088 (RO)
- Cohorte **11 / 50 (piso; estimado 55)**. Un solo page_id, un solo producto: el título del ad es el mismo nombre del producto («Atlas Terapeutic Vizual») + variantes «12 Abordări Terapeutice într-un Singur Loc», «32 de Metafore Vizuale pentru Terapie», «Index și Fluxograme pentru Ședință», «6 Pași în Fiecare Temă», «Găsește Tema în Câteva Secunde».
- Escalonamiento: tandas creadas 11-05/06, 11-09 (≈ 6 ads), 11-11 (≈ 6), 11-13, 11-14/15 (~7 hoy/ayer); ≥ 6 fechas distintas, ≥ 1 en los últimos 30 días: no zombi. Longevidad máx. ≈ 11,7 días por API (inicio 2026-11-05). El resto de los 50 más nuevos tiene 1-6 días: la cohorte crece sola en los próximos días.
- Moneda de la cuenta: ARS (operador argentino que hace llegar el producto en rumano a RO → arbitraje de idioma).
- Qué vende (por títulos): atlas visual para psicoterapeutas: 12 enfoques terapéuticos, 32 metáforas visuales, índice y flujogramas para sesión, búsqueda de tema. Formato probablemente PDF/atlas digital. Precio y landing: no vistos.
- Marca personal: nombre de página = producto, no persona; no se ve cara en los títulos.
- Hermanos: «Atlas Visual Academy» (MX, atlas de enfermería), «Atlante Visivo» (IT): red de atlas visuales profesionales.

### 2. Studio Facile (catálogo «X în imagini») — señal, no tarjeta
- p. 1232011766670582: **39 / 48** con 7+ días; p. 1272162682644374: **15 / 50 (piso; estimado 56)**. Inicio de ads desde 2026-10-28 (≈ 19 d). USD.
- ~25 temas distintos, ninguno ≥ 10 (Contabilitatea 6, Sudura 6, Teoria muzicii 5, Psihologia 4, Naviația 4, Fizioterapia 6 + 1, PLC 5, Electronica 5). Creativo genérico «Răsfoiește înainte să descarci» ≈ 15 ads. Si es un catálogo único la lectura cambia; no verificable desde la nube. Se deja como señal por criterio previo de la sesión RO.

## Veredicto provisorio
Atlas Terapeutic Vizual: **observar / ENTRAR a evaluar → ya corre en RO** (fuente = RO, el producto ya existe en rumano; para el dueño: modelar atlas visual de psicología/terapia en RO, y medir FR/IT/PT/BR). Studio Facile: observar.

## Cobertura
| Keyword / conteo | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| page_id Studio Facile 1272162682644374 | RO | 56 est. (50 vistos) | — | 15/50 piso, ~15 temas |
| page_id Studio Facile 1232011766670582 | RO | 48 | — | 39/48, ~14 temas |
| `explicat prin desene` | RO | 0 | no corrido | 0 (trampa: matcher AND exige las dos palabras en el texto, no solo en título) |
| `ghid ilustrat` | RO | 52 est. | — | Pagina de Nursing, Știința Bunicilor/Textomat, Coach Eva Natural (lead gen), Digital Books/Neuralforkids, Nora Holm, Editura Dabomed |
| `hărți mentale` | RO | 101 est. | — | Atlas Terapeutic Vizual (descubrimiento), Ready Resources, Impulso Digital |
| `în imagini pdf` | RO | 116 est. | — | Studio Facile, Diagram Books, Nexo Digital, Magistium |
| page_id Pagina de Nursing 340055433511635 | RO | 21 | — | ≈ 20/21 con 7+ d; mezcla ghiduri ilustrate + clipboard/insigne/pachete (físico) |
| page_id Ready Resources 1440348585824077 | RO | 30 | — | 5/30 (Biologie cl. IX, tanda de hoy de ~20 más) |
| page_id Atlas Terapeutic Vizual 1408033785736088 | RO | 55 est. (50 vistos) | — | 11/50 piso |

Keywords nativas distintas: 4 + 4 conteos por page_id adicionales. No se corrió `ALL` (no hubo cero que explicar salvo `explicat prin desene`, que es trampa de matcher).

Trampas nuevas: `explicat prin desene` da 0 aunque Studio Facile lo usa en títulos (el matcher mira el cuerpo, no `ad_creative_link_title`); usar `în imagini` + `hărți mentale` para descubrir atlas/mapas en RO.

Nodos nuevos propuestos: atlas-psicoterapia-ro (Atlas Terapeutic Vizual, 11/50), nursing-ghiduri-ro (Pagina de Nursing, ~20/21 mezcla física), biologie-liceu-ready-resources (5/30), mapas-enfermeria-ro-impulso (Impulso Digital, 300 hărți mentale asistent medical, BRL, 5 ads de hoy).

## Lo que no se pudo verificar
- Landing, precio y formato de Atlas Terapeutic Vizual (la API no trae URL; snapshot 403 desde la nube).
- Si Studio Facile es catálogo único o libros sueltos.
- Si Pagina de Nursing vende digital o impreso (parte es claramente física: clipboard, insigne).
