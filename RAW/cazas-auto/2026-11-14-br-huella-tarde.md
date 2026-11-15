# Caza automática — BR · A huella · sin nodo — 2026-11-14 (sáb; corrida de noche, 23:41 America/Santiago)

Modo: sábado = C agenda, pero la agenda de `cazas.md` y «Operadores a seguir» están vacías y la cola solo tiene los 3 nodos 🔴 → cola vacía → modo A (regla del prompt BR §6). Ahora ≈ epoch 1794711000; cohorte 7+ = `ad_creation_time` ≤ ~1794106000.

## Shortlist
Ninguna página llegó a cohorte 10 (por page_id, BR, ACTIVE). Nada pasa la vara.

| Página | page_id | Qué vende (por título/copy) | Cohorte 7+/activos BR | Nota |
|---|---|---|---|---|
| Riscos para Bordar | 396283016894466 | moldes de bordado (digital) | 7 / 16 | más cercana; 7 ads creados hace ~9 d, 3 hoy, 6 hace ~2 d; 3+ fechas, operador vivo; no llega a 10; embudo no verificado (sin URL en la API) |
| Tudo sobre unhas | 106958424923732 | fábrica multi-SKU (packs de mapas visuales, moldes, proyectos eléctrica/serralería, diagramas) con nombre de página que no corresponde | 1 / 36 | 8+ SKU distintos, casi todo creado en las últimas 2 semanas; también corre recetas (nicho excluido, ignorado) |
| Mapas e Guias Visuais | 1394868680373327 | mapas visuales (NBR 9050) | 0 / ≥50 (127 estimados) | los 50 devueltos son de hace ~22 h, una sola tanda; cohorte no medible (limit 50 sin paginado) |
| Mapa Mestre | 1106252972577829 | mapas mentais | 3 / 6 | |
| SharkAprova | 109283044755241 | 100 mapas + 3 bonos R$ 27,90 | 0 / 6 | |
| Francês do Zero à Fluência | 1345708028634196 | +300 mapas mentais de francés | 0 / 5 | |
| Manual da T.G | 1447298968471299 | Manual Prático R$ 37,90 | 0 / 5 | |
| Parar de Fumar de Vez | 1436509976219606 | Guia Prático 30 días (Hotmart) | 0 / 6 | |
| Guia Prático do BPC | 1352320024642250 | guías auxilio-maternidad R$ 19,90 / BPC | 0 / 4 (2 de hace 5-6 d) | |
| Meu Natal Criativo | 1473602429162241 | +400 moldes de Natal | 0 / 10 | todo creado hoy |
| Nasce um corredor | 1357307207470608 | Do sofá aos 5K | 0 / 10 | todo creado hoy |
| Sofia atividades para crianças | 1527322473786659 | kit atividades / fala | 0 / 5 | |
| Planilha na Prática | 1532384003286959 | planillas + curso de Excel | 3 / 3 en BR (creados hace ~3 d) | |
| Valença | 1535863232934394 | finanzas personales | 0 / 3 | |
| Estante da Fé | 1451536618037972 | sin título | 0 / 0 (ACTIVE devolvió 0 al contar por page_id) | anotar como desaparecida si se repite |

## Veredicto provisorio
Sin candidatos a tarjeta. Observar: mapas visuales/mentais (varias páginas: Mapa Mestre, SharkAprova, Francês…, Tudo sobre unhas, Mapas e Guias Visuais) como nicho emergente; Riscos para Bordar (7/16) a re-medir. Par fuente→destino no aplica todavía. Nunca DESCARTAR.

## Cobertura
| Keyword | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| guia prático pdf | BR+PT | 1127 est. (50 leídos) | no | páginas de guías (BPC, parar de fumar, T.G, Valença), mucho ruido de la tanda de hoy |
| planilha pronta | BR+PT | 1177 | no | planillas, CRM, software; maxplanilhas, Obranaplanilha |
| mapas mentais | BR+PT | 6452 | no | red de mapas visuales (SharkAprova, Mapa Mestre, Lulu Concurseira, Saber digital) |
| ebook completo | BR+PT | 5355 | no | Riscos para Bordar, Tudo sobre unhas, ebooks sueltos |
| acesso vitalício | BR+PT | 55352 | no | mucho ruido (geladeiras, cursos con cara); Meu Natal Criativo, Planilha na Prática |
| material digital | BR+PT | 16142 | no | Tudo sobre unhas, Sofia, Mapas e Guias Visuais |
Conteos por page_id + countries:["BR"] ACTIVE sobre 16 páginas (tabla de arriba). PT no se midió por página (las páginas halladas son BR). 6 huellas de las ~8-12 del modo A (resto de huellas: `hotmart`/`kiwify` anchas no se corrieron: la cola de BR dice que sirven solo para leer nombres).

Trampas nuevas: (1) páginas «cáscara» con nombre ajeno al producto (Tudo sobre unhas vende mapas/moldes/proyectos): el page_name no dice el nicho, leer el título del ad. (2) `currency: USD` en ads BR no indica otro país. (3) Con `limit:50` una página con tanda masiva del día anterior (Mapas e Guias Visuais, 127 est.) devuelve solo ads de hace ~22 h: cohorte no medible, no confundir con 0.

## Lo que no se pudo verificar
Longevidad real y embudo/precio: la API de esta corrida no trae el copy ni la URL de landing (solo título), `ad_snapshot_url` da 403 desde la nube → «embudo no verificado desde la nube». Precios solo los que aparecen en el título (R$ 19,90 / 27,90 / 37,90). Marca personal no evaluable en snapshots.
