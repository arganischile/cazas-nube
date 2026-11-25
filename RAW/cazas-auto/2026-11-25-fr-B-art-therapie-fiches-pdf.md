# Caza FR · 2026-11-25 (mañana) · B perforar · art-therapie-fiches-pdf

Sesión FR en la nube, desatendida. Modo del día: miércoles → B perforar. Nodo: `art-therapie-fiches-pdf`
(virgen FR más viejo; último toque 2026-11-18, ≥ 7 d). Evidencia: API `ads_library_search`
(`countries: ["FR"]`), sin navegador; snapshots y embudos no verificados desde la nube (los ads no traen URL
de landing en la API). Longevidad = hoy − `ad_creation_time` (corrida 2026-11-25 06:41 CLT).

## Cobertura

Keywords nativas (FR, ACTIVE salvo indicación):

| Keyword | Est. | Qué trajo |
|---|---|---|
| `art-thérapie activités` | 24 | Manual de Arte Terapia (8), Atelier delle Emozioni, Luísa Carvalho, formaciones (Equilibre Formation, Efficient Coach) |
| `fiches art thérapie` | 3 | ruido (Glaure físico, formación Instruire Bien-Être) |
| `journal créatif` | 21 | Sofi Journaling 0/4, Free Books Club (lead magnet), papelería física |
| `mandalas thérapeutiques pdf` | 6 | ProfessionalHub «atelier mandala en EHPAD» → **nicho excluido (adulto mayor), ignorado** |
| `ateliers créatifs prêts à l'emploi` | 0 | — |
| `activités gestion des émotions adultes` | 2 | ruido |
| `art-thérapie enfants fiches` (ALL) | 5 | Carol Miller Fabric Art «300 outils thérapeutiques» (0 activos en FR por page_id), Anna «1 257 outils» |
| `outils thérapeutiques à imprimer` | 54 | **Therapy Toolkit** (kit thérapeutique pour adolescents), Louis Martin, Florence Garnier, AprendreKids |
| `fiches psychoéducation adolescents` | 11 | **NeuroKit Clínico** (fiches TCC / deuil) |
| `Kit thérapeutique pour adolescents` | 47 | conteo del SKU FR de Therapy Toolkit |

Subnichos mirados: art-thérapie adultos (actividades en casa), journaling, mandalas, art-thérapie infantil,
kits de herramientas terapéuticas para profesionales (adolescentes, TCC, duelo).

## Conteos por page_id (FR)

| Página | page_id | Cohorte 7+ / activos | Fechas | Notas |
|---|---|---|---|---|
| Therapy Toolkit | 102506312071455 | **≥ 29 / 47** (SKU FR «Kit thérapeutique pour adolescents»; página 96 est., multilingüe, piso) | 09-26 ×9, 10-14 ×20, 11-19 ×18 (FR); + EN «21 Mental Reprogramming Protocols» 11-13, «Teen Therapy Toolkit» 10-14/11-19, IT «Kit di risorse terapeutiche» | USD; ad más viejo ≈ 60 d; en PT/BR/RO solo creativos en inglés (90 est.), en IT tiene SKU italiano |
| NeuroKit Clínico | 883009701566343 | **30 / 31** FR (+1 ES) | 10-14 ×7, 10-22 ×6, 11-08 ×7, 11-12 ×1, 11-15 ×9 | BRL (operador BR); multi-SKU para terapeutas: «90 fiches TCC prêtes pour la séance», «Le Kit TCC Enfants», «78 fiches de deuil», «6 programmes · 12 séances», «Guidance parentale déjà prête»; en IT/RO/PT/BR corre los mismos creativos FR/ES (25 est.), sin SKU nativo |
| Atelier delle Emozioni | 1338748315990304 | 8 / 15 en francés (29/39 todos los idiomas; IT: 53 est.) | 10-28 → 11-24, 13 fechas | USD; multilingüe IT/FR/DE; «Pas besoin de savoir dessiner», «120 schede», «meno di 15 €»; trampa de idioma: en FR solo cuentan 8 |
| Manual de Arte Terapia | 1213147361873813 | 0 / 8 | una sola tanda 11-20 | rotó todo (antes 5/17, 4/16); «100 activités + 6 bonus» |
| Florence Garnier | 1336756022834844 | 7 / 9 | 10-06 → 11-20 | BRL; «241 dynamiques thérapeutiques prêtes à l'emploi»; nombre de persona (¿fantasía?) |
| Louis Martin | 448576148332682 | 4 / 4 | una tanda 10-23 (≈ 32 d) | BRL; «250 cartes mentales thérapeutiques»; posible zombi (ningún ad en 30 d) |
| Luísa Carvalho | 1166297423222806 | 0 / 4 | 11-20 → 11-25 | BRL; «150 ressources d'Art-Thérapie prêtes à imprimer» |
| Sofi Journaling | 1337522202788282 | 0 / 4 | 11-24/25 | USD; «kit complet de journaling» |
| Anna | 1323278090859741 | 0 / 1 | 11-22 | BRL; «1 257 outils prêts à l'emploi» |
| Carol Miller Fabric Art | 1236178462916578 | 0 activos FR | — | «300 outils thérapeutiques prêts à imprimer» |

## Gate

- **Therapy Toolkit**: no marca personal (página genérica); infoproducto probable (kit de recursos para
  terapeutas/padres de adolescentes, «kit» podría ser físico → verificar en la PC); no excluido; no está en
  `descartados.md` ni en `wiki/productos/`. Zombi: 3+ fechas y tanda del 11-19 → vivo. **Pasa la vara.**
- **NeuroKit Clínico**: página genérica; fichas imprimibles para terapeutas (digital); no excluido; no en
  descartados ni fichas. 5 fechas, última 11-15 → vivo. **Pasa la vara.**
- Embudo de ambos: la API no trae URL de landing → «no verificado desde la nube».

## Decisiones por default (sesión desatendida)

- Se contó solo el creativo en francés (trampa de idioma de la cola): Atelier delle Emozioni queda en 8.
- ProfessionalHub (mandalas en EHPAD) cae en el nicho excluido actividades-adulto-mayor: no se agrega a la cola
  ni va como señal.
- Ambas tarjetas son ofertas distintas (dos operadores, dos productos) del mismo eje «kits de herramientas
  terapéuticas imprimibles para profesionales»: el eje que escala no es art-thérapie de consumo sino el
  material listo para la sesión del terapeuta.

## Nodo

`art-therapie-fiches-pdf` → superficial (8 keywords + 2 conteos de SKU, ALL en una). Hijos nuevos `virgen`:
`kit-therapeutique-ados-therapy-toolkit-fr` y `fiches-tcc-neurokit-clinico-fr`.
