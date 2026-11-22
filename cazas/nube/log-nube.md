# Log técnico de la nube

| Fecha | Sesión | Qué pasó |
|---|---|---|
| 2026-11-14 | BR | Prueba manual: el clon de la nube quedó en la rama `main-xd7v5t`; `git push origin main` no empujaba y el hook de cierre subió esa rama. Corregido en NUBE.md §2.0 (checkout -B main) y §3 (push HEAD:main). |
| 2026-11-22 | FR | Segunda corrida de la rutina un domingo (09:32 America/Santiago), con el lint de FR ya hecho y pusheado hoy (RAW/cazas-auto/2026-11-22-fr-lint-cola.md). No se repitió ni se tocaron la cola ni la bandeja. |
| 2026-11-22 | EU | Corrió una rutina «Caza automática · EU» (09:38 America/Santiago) que no figura en `cazas/nube/rutinas.md`; su prompt pide `cazas/nube/prompts/eu.md`, que no existe (solo br, it, fr, ro, mx, co). No cazó ni tocó cola ni bandeja. Probable rutina vieja que quedó activa: revisarla en claude.ai/code/routines y pausarla o borrarla. |
| 2026-11-22 | EU | Segunda corrida de la rutina vieja «Caza automática · EU» (09:43 America/Santiago), otra vez sin `cazas/nube/prompts/eu.md`. No cazó ni tocó cola ni bandeja. Sigue activa: pausarla o borrarla en claude.ai/code/routines. |
