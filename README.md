# Óscar Mena Vílchez · Alcaldía Provincial de Cutervo 2026 — portal de campaña

Sitio estático (HTML/CSS/JS sin dependencias) con el discurso, la presentación de los ejes del plan, el mapa interactivo
de los 15 distritos (electores por distrito y local de votación, pobreza, servicios básicos, salud, educación, demandas GEMSES)
y los documentos de la campaña, que se van acumulando.

- `index.html` portada · `discurso.html` · `ejes.html` · `mapa.html` · `documentos.html`
- `docs/` PDF y Word del discurso · `datos/` bases con fuente (CSV/JSON/MD) · `img/` mapas PNG y portada

Fuentes: INEI (Censos 2017/2025, Mapa de Pobreza 2018, Directorio CCPP 2017, capa CCPP IGN), ONPE (EG2026 1.ª y 2.ª vuelta),
RENIEC, SUSALUD (RENIPRESS 2026), CEPLAN-PCM (brechas territoriales), MINEDU/GORE Cajamarca, MININTER, MEF, SERNANP.
Generado con los scripts de `p23_GEM_POLITICA/tools/` (extraer datos → integrar distritos → mapas → Word/PDF → sitio). Actualizado: 23 de agosto de 2026.
