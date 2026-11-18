# Caza automática — FR · B perforar · ressources-neuro-imprimables — 2026-11-18

Evidencia: API (`ads_library_search`); snapshot y embudo no verificados desde la nube. Longevidad por API.
Hoy ≈ epoch 1794995000; corte de 7 días ≈ 1794390000.

## Shortlist

### 1) «210 Fiches Visuelles sur les Troubles Mentaux» — Esprit Académique (p. 1229441186928180), FR
- Cohorte 7+ / activos: **≥ 50 / 95 estimados** (limit 50 = piso; los 50 devueltos tienen todos `ad_creation_time` ≥ 11,6 días). Moneda BRL (operador brasileño, creativo traducido al francés).
- Escalonamiento por fechas de creación: 10-11 (≈ 37 d), 10-12/13, 10-26, 11-01, 11-06 (≥ 5 tandas); un solo título «🧠 210 Fiches Visuelles sur les Troubles Mentaux» repetido en los 50 (duplicación total).
- Zombis (NUBE §4): ≥ 3 fechas distintas y ≥ 1 ad de los últimos 30 días → no es zombi. Nota: el ad más nuevo tiene ≈ 12 d (sin tanda nueva desde el 11-06); un ad reiniciado el 11-12 (delivery start).
- Marca personal: no (nombre de página = marca/producto, sin cara en los títulos).
- Embudo: no verificado desde la nube (el API no trae URL). Producto probable: pack PDF de 210 fichas de psicopatología (estudiantes de psicología).
- Red del mismo molde en FR (misma oferta «210 fiches visuelles de psychopathologie»): Atlas Visuel de Psychopathologie (1411042928762002) 0/7, ads de 1-4 d, copy «+2100 personnes ont acheté»; Bienestar Consciente (453014791222606) 0/5, ≤ 6 d; Psyacademy (944317715424068) 0/5, ≤ 6 d. Cuatro páginas con la misma oferta = prueba de duplicación entre operadores.
- Score provisorio 2/4 (① longevidad 45+ no: ≈ 37 d; ② volumen 50+ sí piso; ③ duplicación sí; ④ hueco: IT cerrándose con 3 jugadores, PT/RO sin Esprit).

### Señales de destino (misma familia, no tarjetas)
- IT: Elena Marchetti «Psicologia in Mappe – 220 schede del DSM-5-TR» (1457046367488586) 0/8 (≤ 3,4 d); Prof Priscille «250 disturbi mentali in schede visive» (965309913332032) 0/4 (hoy); Psicopatologia Visiva «200 schede» (1442146142313710) 0/8 (≤ 4,3 d). Ventana IT abierta pero ya con 3 testers.
- RO: Materiale Gata (1442558368941704) 0/3, «240 de fișe vizuale de psihopatologie», «69 lei», tanda ≈ 4 d (cuenta MXN). Harta Tulburărilor RO 1/23 (11-16).
- PT/BR: «210 fichas visuais» da 0 en PT/BR con la keyword literal (Esprit no corre en IT/PT/RO: 0 con page_ids).

## Veredicto provisorio
ENTRAR / observar → molde «fichas visuales de psicopatología (DSM) por tema»: fuente FR (Esprit, operador BR) → destinos IT (3 testers de ≤ 4 d, ventana abriéndose), RO (1 tester de ≤ 4 d), PT sin medir con nativas (`psicopatologia fichas visuais` PT = 0). No DESCARTAR.

## Otros conteos del nodo `ressources-neuro-imprimables`
- Boîte à Ressources Neuro (1345809441959313): ACTIVE 0/6, todos de ≈ 2,1 d (tanda del 11-16); `ALL` = 6 igual. Barrido superficial, re-medir ~11-22.
- Keywords: `ressources imprimables TDAH` = 0; `autisme fiches visuelles` 5 resultados (Sara Fialho – Psicopedagoga, 3 ads «En savoir plus», servicio; Esprit Académique); `dyslexie fiches` 3 (Sara Fialho, servicio); `émotions enfants cartes` 116 (ruido short-drama Sueñovela Amor, Bavardons Parentalité, Anna 1 257 outils); `art-thérapie fiches` 6.

## Otros conteos
- Manual de Arte Terapia (1213147361873813): 4/16 en FR (cohorte 7+: 4 ads de 14-24 d; el resto de la tanda 11-15/16): «Un achat, sept PDF», «1 manuel, 100 activités + 6 bonus»; a 6 de la vara.
- Bibliothèque Créative (Cricut, 1501332446389326): 0/6 (el más viejo ≈ 3,4 d).
- Inspiracion Studio (1096725376864125): «Plus de 130 guides visuels pour Cricut Design Space», USD: 8/10 con 7+ d (creaciones 24-37 d, 2 ads de hoy); a 2 de la vara. Trenly Group (604874792719971) 1 ad «150 guides Inkscape et Ink/Stitch».
- Anna (1323278090859741): 6 ads FR (5 «1 257 outils prêts à l'emploi» BRL, 1 en italiano), 2/6 con 7+ d; sin vara.

## Cobertura
| Keyword | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| (page_id Boîte à Ressources Neuro) | FR | 0 | 6 | 6 ads de 2 d, 0 cohorte |
| ressources imprimables TDAH | FR | 0 | — | nada |
| autisme fiches visuelles | FR | 5 | — | Sara Fialho (servicio), Esprit Académique |
| émotions enfants cartes | FR | 116 | — | ruido short-drama; Anna, Bavardons Parentalité |
| art-thérapie fiches | FR | 6 | — | Manual de Arte Terapia |
| dyslexie fiches | FR | 3 | — | Sara Fialho (servicio) |
| guides visuels cricut | FR | 17 | — | Inspiracion Studio, Trenly, Bibliothèque Créative |
| fiches visuelles troubles | FR | 106 | — | red 210 fiches psicopatología |
| 210 schede visive disturbi mentali / psicopatologia schede visive | IT | 0 / 20 | — | 3 jugadores |
| 210 fichas visuais transtornos mentais / psicopatologia fichas visuais | PT(+BR) | 0 / 0 | — | vacío con las nativas barridas |
| fișe vizuale psihopatologie | RO | 3 | — | Materiale Gata |
| page_ids ×~12 con countries | FR/IT/PT/RO | | | ver arriba |

Trampas nuevas: `émotions enfants cartes` en FR trae short-dramas (Sueñovela Amor) y coaching de parentalidad; `ressources imprimables TDAH` da 0 (nicho neurodivergente casi vacío en FR); `fiches visuelles troubles` es la huella que descubre la red de psicopatología (106 resultados).
Nodos nuevos propuestos: `psicopatologia-fichas-visuales-esprit` (FR), `cricut-guias-visuales-inspiracion` (FR).

## Lo que no se pudo verificar
Embudo/precio/landing de todos los candidatos (el API no trae URL ni cuerpo); snapshots; si Esprit corre desde BR en portugués (no se midió BR con la oferta en portugués por page_id distinto).
