# Caza automática — IT · A huella · — 2026-11-18

Hora de corrida: 2026-11-18 06:36 America/Santiago (epoch 1794994588). Umbral cohorte 7+ d: creación ≤ 1794389788.
Evidencia: API (`ads_library_search`); snapshot y embudo no verificados desde la nube (las respuestas de la API no traen URL de landing ni cuerpo del ad).

## Shortlist

### Kit Contabile Pratico 2027 · 7 quaderni + 8 bonus — Giulia Ferraresi (page_id 1299765756564104) IT
- Ads Library IT: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=IT&is_targeted_country=false&media_type=all&search_type=page&sort_data[direction]=desc&sort_data[mode]=total_impressions&view_all_page_id=1299765756564104
- Cohorte: **11 de 50 ads activos con 7+ días** (50 = piso de la API; estimado 146 activos). Un solo page_id, un solo título («Kit Contabile Pratico 2027 · 7 quaderni + 8 bonus»), moneda de cuenta USD.
- Escalonamiento: 6 tandas de creación (≈ 11-09 con 9 ads de la cohorte, 11-10 con 2, 11-11 con 6, 11-14 con ≈ 8, 11-16 con ≈ 12, 11-17 con ≈ 13). ≥ 3 fechas distintas y ads de los últimos 30 días (zombi descartado). Los 6 ads de la tanda del 11-11 cruzan 7 d en las próximas horas, así que la cohorte sube a ≥ 17 hoy.
- Longevidad por API: los 11 de la cohorte con `ad_delivery_start_time` entre 7,0 y 8,7 días; máx. visto ≈ 8,7 d (la página tiene hasta 146, los más viejos quedan fuera de los 50).
- Tipo de página: nombre = persona (Giulia Ferraresi), pero los títulos venden el producto (kit, 7 cuadernos, 8 bonus), sin cara ni nombre propio en el copy → marca personal no evidenciada; verificar en la PC.
- Embudo: no verificado (sin URL en la API).
- Misma oferta que FR (Amélie Boissieu, Kit Comptable 2027, tarjeta en bandeja ≥32/50) y molde RO (Contador en Acción, MARCO MEDIA): el kit de cuadernos contables se valida en IT, FR y RO.

## Veredicto provisorio
ENTRAR → IT (ya hay operador local con 11/50) y FR/RO ya tienen molde; destino a medir: PT. Estacional (año nuevo 2027). Nunca DESCARTAR.

## Cobertura
| Keyword / conteo | País | ACTIVE | Qué trajo |
|---|---|---|---|
| schede stampabili | IT | 56 | Editorial Atlas (kit recupero matematica, 0/23 por page_id), Salud Didáctica, Nova Skills, Bright Digital Hub, ruido |
| quaderno esercizi | IT | 732 | Studio Facile (tandas de ayer), Nova Skills, **Giulia Ferraresi (kit contabile)**, Grammatica al Volo |
| modelli editabili | IT | 5 | casi vacío (inmobiliarias, PartyKit) |
| guida pratica scaricabile | IT | 6 | casi vacío (Maker district, Studio Facile viejos) |
| schemi pdf | IT | 801 | crochet/punto croce (excluido, ignorado), InventaLab, Meccanica Industriale Visiva, Digital solutions, Bright Path Learning, Professoressa Giulia, red BRL de otros mercados |
| pacchetto digitale bonus | IT | 197 | InventaLab, Giulia Ferraresi, Natale Senza Stress |
| fogli di lavoro bambini | IT | 17 | ruido (trading, camper, remedios) |
| checklist pronta | IT | 75 | ruido, Lighter Life, Camille Dubois, Download Studio |
| conteo page_ids | IT | — | Salud Did. 5/52; Editorial Atlas 0/23; Nova Skills 0/5; Studio Facile 0/50 (cohorte no medible, 648 est.); Giulia Ferraresi 11/50 piso; InventaLab 0/50 (153 est., multi-idioma); Bright Path Learning 0/13; Meccanica Ind. Visiva 0/3; Digital solutions 12/50 (multi-SKU); I 6 Segreti 0/13; Camille Dubois 9/9; Lighter Life 0/9; Download Studio 2/50 (EN) |

Señales: Digital solutions (1406571882531997) 12/50 (50 = total) pero repartido en ofertas: «Kit Formazione Sicurezza 2026 · 17,90 €» + «+1.200 slide in 46 corsi» ≈ 8, «Dal corso all'ambulanza, in un solo manuale» ≈ 4, «120 prompt per ingegneri» ≈ 1; ninguna oferta sola llega a 10. Camille Dubois (1435613592973828) 9/9 «L'IA pronta per chi lavora nell'HR» (USD), a 1 de la vara, sin ads nuevos. Salud Didáctica (1060368773817749) 5/52, manuales clínicos para médicos, ads de 0-12 d (tandas diarias). InventaLab 153 est., «Oltre 120 progetti con materiali di casa» en IT/PL/CZ/RO, 0/50 (todo ≤ 1,5 d de creación en los 50 más nuevos; cohorte no medible). Studio Facile en IT 648 est., tandas diarias de ≈50 por día (concorsi, mappe, ayurveda, razze, nail art): cohorte no medible; ligar con libros-visuales-en-imagenes-ro.

Trampas nuevas: `schemi pdf` en IT trae crochet/punto croce (excluido), anunciantes BRL de otros mercados (Katie McDow, Priscila Vermont, Professoressa Giulia) y tiendas ecommerce; `modelli editabili` y `guida pratica scaricabile` casi vacíos; `checklist pronta` ruido de inmobiliarias y servicios.

Nodos nuevos propuestos para la cola: `kit-contabile-pratico-2027-it` (superficial → ver card), `sicurezza-lavoro-slide-digital-solutions` (virgen), `progetti-bambini-inventalab` (virgen).

## Lo que no se pudo verificar
Landing, precio y marca personal de Giulia Ferraresi (la API no trae URL ni cuerpo); si Digital solutions vende PDF/slides o cursos; si InventaLab es físico (kits) o digital.
