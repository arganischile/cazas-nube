# Caza automática — RO · A huella · — — 2026-11-19 (jueves, mañana)

Evidencia: API (`ads_library_search`); snapshot y embudo no verificados desde la nube (la API no trae URL de landing ni cuerpo del ad). Hora de referencia 06:45 America/Santiago ≈ epoch 1795081500; 7 días atrás = 1794476700.

## Shortlist

### Tuformulaexactashop — «Tot Civilul în 350 de fișe vizuale» (p. 1332330876634506)
- Ads Library RO: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=RO&view_all_page_id=1332330876634506
- Cohorte **12 / 22 activos** (ACTIVE, `page_ids` + RO). Los 12: 5 «Tot Civilul în 350 de fișe vizuale» (creación ≈ 8,8 d) + 4 «+BONUSURI CADOU» (≈ 8,8 d) + 3 «+BONUSURI CADOU» (≈ 8,2 d); todos con inicio de entrega a 8,0-9,0 d. Los otros 10 son tanda de hoy (11-18/19, «Tot Civilul…» ×5 y «+BONUSURI CADOU» ×5).
- Total histórico ALL: 169 estimados (50 vistos); en ALL aparecen tandas intermedias ya apagadas (11-14: «Trei zile până la examen», «Un subiect pe o pagină, nu pe treizeci»; 11-16/17: «Tot Civilul și tot Penalul în 700 de fișe», «Tot Penalul în 350 de fișe», «Pachetul complet SSM pentru instructaj», «Peste 240 de fișe» instructaj). El operador rota tandas cada 2-3 días: 3 fechas de creación distintas entre los ads con 7+ d (11-09, 11-10, y 11-11) → pasa el filtro de zombis (≥ 3 fechas, ≥ 1 ad de los últimos 30 d).
- Ads con ARS (3, «Tot Penalul», 11-08) = misma cuenta anunciante operando también otro mercado.
- Moneda de la cuenta USD (RO como mercado entregado), creativos 100 % en rumano.
- Oferta (por título): «Tot Civilul în 350 de fișe vizuale» (⚖️ derecho civil, fichas visuales para estudiantes/examen: «Trei zile până la examen», «Un subiect pe o pagină, nu pe treizeci», «Nu înlocuiește cursul. Ți-l pune în ordine», «Aceeași materie, pusă în ordine»), «Tot Penalul în 350 de fișe», bundle «700 de fișe» Civil+Penal y un segundo producto de **SSM / instructaj** («Pachetul complet SSM pentru instructaj», «Instructajul pe domenii, în fișe ilustrate», «Peste 240 de fișe»). «+BONUSURI CADOU». CTA «Te interesează? Apasă pe Cumpără» (tienda con botón Comprar).
- Tipo de página: tienda sin cara (nombre de página «Tuformulaexactashop»); no hay persona en los títulos. Gate de marca personal: pasa.
- Embudo: no verificado (API sin URL). Precio: no se sabe.
- Molde: mismo formato «X en fișe vizuale» de Studio Facile, Esprit Académique/Atlas de psicopatología (nodos `libros-visuales-en-imagenes-ro`, `psicopatologia-fichas-visuales-fr`) aplicado a **derecho** (examen de licență/barou/magistratura) y a **SSM** (cursos obligatorios de seguridad laboral, ver `sicurezza-lavoro-slide-digital-solutions` en IT).

## Veredicto provisorio
ENTRAR → molde «fișe vizuale» de derecho en RO (el mercado ya lo corre). Derecho depende del país: el código civil/penal rumano no se traslada tal cual; el molde sí. Cruce: `schede visive diritto civile` IT = 0, `fiches visuelles droit civil` FR = 0, `direito civil fichas visuais` BR/PT = 8 resultados, 6 de «Fichas do Técnico Judiciário» (p. 659405190583573, todos de hoy 11-18/19, concursos TJ/TRT/TRE «a partir de R$ 10», moneda USD, 0 con 7+ d) → el molde de «fichas por concurso» existe en BR con tanda de hoy. Hueco: IT/FR/PT (con ALL no se corrió: IT/FR dieron 0 en ACTIVE; no se declara vacío, quedó como superficial).
Par fuente → destino: RO (fuente y destino); adaptar a IT/FR/PT/BR por códigos nacionales (no probado).

## Cobertura
| Keyword | País | ACTIVE | ALL | Qué trajo |
|---|---|---|---|---|
| ghid complet pdf | RO | 28 | — | Digital Master (cor, USD), Garden Atlas Studio (acuarela, EN/RO, USD, tanda de hoy), PutereaMintii (19 lei «De unde vine?», tanda de 3 d), Maria Matyas (persona) |
| agendă planificator | RO | 1 | — | Meli Melo (ecommerce físico) — ruido |
| fișe pdf descarcă | RO | 60 | — | **Tuformulaexactashop**, Studio Facile (2 page_id), Rowan House Press, Med Atlas 0/4, Edulabs, Download Studio, Dragana Savić («135 de povești», tanda de hoy) |
| manual practic pdf | RO | 2 | — | Coach Eva Natural (CLP, lead magnet), Caffeine Institute (EN) — ruido |
| fișe vizuale | RO | 52 | — | Tuformulaexactashop, Harta Tulburărilor, Kit Online (multilingüe), Linkia, Materiale Gata, Fișe de patologie, Atelier Visuel, Cuisine Visuelle |
| plan lecție descarcă | RO | 0 | — | vacío |
| schede visive diritto civile | IT | 0 | no corrido | — |
| fiches visuelles droit civil | FR | 0 | no corrido | — |
| direito civil fichas visuais | BR,PT | 8 | — | Fichas do Técnico Judiciário (6, de hoy), fichasdaflavia (2, viejos 2025) |
Conteos por page_id (RO): Tuformulaexactashop **12/22** (ACTIVE; 50 vistos con ALL, 169 est.) · Digital Master 0/8 (por delivery start; creados 11-12/11-18; coro/«Kit de Tipare pentru Masă» de ALL ya apagados) · Med Atlas 0/4 (11-11, ads de 6,7 d) · Download Studio 50 vistos, casi todo inglés (nicho coach de gimnasia/pilates/foto; rumano ≤ 6 ads) → cáscara USD, no es oferta RO · Kit Online 157 est., multilingüe (HU/CZ/PL/TR/HE/RO), en RO solo «Diagnosticare Auto Pro» (hoy) y «Atlas vizual de radiologie» (≈ 6,2 d) → 0 con 7+ d en rumano.
Señales: Harta Tulburărilor 210 fișe 6 ads de hoy + 2 ≥ 7 d (≈ 2/8 ACTIVE en la lista). Linkia «120 de fișe pentru citirea schemelor electronice» 2 ads de hoy. Cuisine Visuelle «60 de fișe tehnice de bucătărie» 1 ad. Atelier Visuel «150 de fișe vizuale de prelucrare» 1 ad (≈ 5 d).
Trampas nuevas: `ghid complet pdf` en RO devuelve 28 ads dominados por 3 operadores en USD y lead magnets; `agendă planificator` = ecommerce; `manual practic pdf` 2 resultados irrelevantes. La palabra que rinde es **`fișe vizuale`** (52 resultados, red completa de fichas) — usarla como huella en RO.
Nodos nuevos propuestos para la cola: `fise-vizuale-drept-ssm-ro` (virgen).

## Lo que no se pudo verificar
Precio, plataforma de venta y si el entregable es PDF descargable o plantilla en otro formato (la API no trae URL ni cuerpo). Longevidad real de los 12 ads: solo por `ad_creation_time` y `ad_delivery_start_time`; snapshot no abierto desde la nube. Las tandas intermedias apagadas (11-14/11-16) indican que el operador rota creativos: la cohorte de 12 puede apagarse al renovar la tanda → re-medir a 3-4 días.
