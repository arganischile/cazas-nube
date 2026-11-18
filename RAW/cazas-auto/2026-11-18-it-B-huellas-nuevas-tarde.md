# Caza automática — IT · B perforar (huellas nuevas) · tarde — 2026-11-18

Todos los nodos IT estaban tocados hace menos de 7 días: se repiten huellas distintas a las de la mañana (modo A). Evidencia solo por API; snapshot y embudo no verificados desde la nube.

## Shortlist

### 1. Metodo Universitario (page_id 1512954825682163) — PASA LA VARA
- Ads Library IT: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=IT&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1512954825682163
- Cohorte: con `page_ids`+`countries` y `search_terms: esame` → 88 est. activos, 50 devueltos; **33 con creación de hace 7+ días** (5 del ≈8,2 d, 21 del ≈8,9 d, 7 de ≈14,2-15,3 d). Sin filtro de keyword: 128 est., ≥20 de 7+ d en los 50 devueltos. Piso (limit 50).
- Longevidad por API: ad más viejo creado hace ≈18 d (inicio de entrega ≈17,9 d); 5 tandas de creación distintas (≈15 d, ≈14 d, ≈8,9 d, ≈8,2 d, ≈4 d, ≈1,4 d) → pasa filtro de zombis (≥3 fechas y ≥1 ad de los últimos 30 días). Snapshot no verificado desde la nube.
- Moneda EUR (operador local). Títulos en italiano nativo.
- Oferta: método de estudio universitario («Metodo OCME», «Super Studente Sales», CTA «Scopri il Metodo»); formato (curso grabado / PDF / mentoría) NO verificable: la API no trae URL ni precio. Hook: «Da 2 esami all'anno a 14», «Posa gli evidenziatori e i riassunti», «Per la patente c'è la scuola guida. Per l'università?», «100 pagine al giorno contro 15».
- Marca personal: nombre de página de marca (no de persona); creativos con testimonios en primera persona («La mia memoria era terribile»); si hay cara se ve en la PC.
- Competidores en el mismo molde en IT: Giovanni DOC Fenu – Metodo di Studio (358643580894881; MemoVia; MARCA PERSONAL, no cuenta; ~15 ads, todos de hoy/ayer) y Powerful Students (511927642001434; 13 ads, todos de ≤ 6,1 d, 0 con 7+ d; EUR).
- Score provisorio 2/4 (cohorte y longevidad OK; embudo/precio/formato sin ver).

## Veredicto provisorio
SUBNICHO/observar → verificar en la PC si es curso grabado o PDF antes de decidir. Si es infoproducto grabado: modelar el método de estudio universitario; destinos a medir: PT, BR (concursos/universidade), FR, RO.

## Cobertura
| Keyword | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| dispense pdf | IT | 59 est. | — | Digital solutions (Sicurezza), Tecnica Visiva, Farmacologia a Colpo d'Occhio (11 ads, ≤1,8 d), Carla Nappi (manicure, curso), Martina Rossi, Pedro Roscoe «100 Procedure Visive OSS» (2 ads, 17,7 d) |
| riassunti concorso | IT | 31 est. | — | red «La Mappa <concorso> 2026/2027» (ASMEL, Assistente ASL, Magistrato Tributario, Vice Ispettore Penitenziario), Martina Rossi (nursing maps), Metodo Universitario, Comuni in Mappe (BRL) |
| bilancio familiare | IT | 158 est. | — | ruido (préstamos, energía, diarios, periódicos, RSOC en USD); nada de infoproducto |
| schede allenamento pdf | IT | 29 est. | — | Studio Facile (ya conocida), Alma Artesana 7/7 (<7 d), Schede di Scienze Motorie 4 ads de ≈23 d (0 en cohorte útil: solo 4), Learning Fast, Nimora Books (CHF) |
| quaderno allenamento | IT | 38 est. | — | Studio Facile, Nimora Books, Fit Click (app), coaches |
| esame (page_ids Metodo Univ.) | IT | 88 est. | — | ver arriba |
| metodo di studio università | IT | 403 est. | — | Giovanni DOC Fenu, Powerful Students, Metodo Universitario, tutor IA, universidades |
| tecniche di studio | IT | 57.854 est. (ALL; ruido: clínicas) | ALL | keyword demasiado ancha, ruido |
Conteos por `page_id`: Martina Rossi 44/44 (0 con 7+ d; el más viejo ≈5,1 d: «Impara Office da zero» ≈25 ads, «200 Mappe Concettuali di Infermieristica» ≈14, «Riesci a risolvere un caso reale?», «+1.000 storie bibliche illustrate»; multi-SKU, USD), Mappe per Concorsi 50/50 piso (0 con 7+ d; todo ≤ 3 d; Magistrato Tributario USD, Agente Immobiliare BRL), La Mappa ASMEL 2026 39/39 (0 con 7+ d; el más viejo ≈4,8 d), Powerful Students 13/13 (0), Schede di Scienze Motorie 4, Alma Artesana 7 (0).

Trampas nuevas: `bilancio familiare` en IT = préstamos/energía/periódicos; `tecniche di studio` con ALL = 57.854 (clínicas «Studio …»: «studio» = consultorio); `metodo di studio università` mezcla universidades y tutores IA; `dispense pdf` trae la red de atlas/mappe ya conocida.

Nodos nuevos propuestos para la cola: `metodo-studio-universitario-it` (virgen→superficial) · `red-la-mappa-concorsi-it` (virgen) · `martina-rossi-multisku-it` (virgen).

## Lo que no se pudo verificar
Embudo, precio y formato de Metodo Universitario (API sin URL); si hay cara en los creativos; snapshots (403 desde la nube).
