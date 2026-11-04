# Panel de constancia en LinkedIn · Kleyi Elimar

Panel personal para sostener el hábito de LinkedIn: datos reales, el "por qué", la semana tipo y un plan de acción con casillas.

**Ver el panel:** https://kleyielimar.github.io/linkedin-panel/

## Qué incluye

- **KPIs del periodo** (8 oct – 4 nov 2026): impresiones, alcance, interacciones y seguidores.
- **Por qué hago esto:** recordatorio para los días de poca energía.
- **Gráficas:** impresiones por día, publicaciones por impresiones y quién te sigue.
- **Semana tipo (≈15 min/día)** y versión mínima para días malos.
- **Plan de acción** con casillas y barra de progreso.
- **Racha semanal** (L–D) para no romper la cadena.
- **Ideas anti-olvido** para anclar el hábito.

> Las casillas y la racha se guardan en el navegador de cada dispositivo (localStorage). No se sincronizan entre móvil y computadora.

## Cómo actualizar los datos (1 vez al mes)

1. Exporta las analíticas desde LinkedIn.
2. Abre `index.html` y busca la sección `// ===== DATA =====`.
3. Sustituye:
   - `daily` → impresiones por día; `dstart` → fecha del primer día (el mes va de 0 a 11).
   - `posts` → `["Título (fecha)", impresiones]`.
   - `aud` → `["Segmento", porcentaje]`.
   - `plan` → las acciones del mes.
4. Actualiza también los 4 KPIs y la línea de fechas en el HTML.
5. Guarda y sube el cambio a `main`. GitHub Pages se actualiza solo en 1–2 minutos.

## Estructura

```
index.html   ← el panel (HTML + CSS + JS en un solo archivo)
README.md    ← este documento
```
