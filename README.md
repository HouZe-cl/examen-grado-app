# Webapp seguimiento Examen de Grado — v3 corregida

Webapp estática para registrar el progreso diario y semanal del estudio del examen de grado de Derecho.

## Uso local

Abrir `index.html` en el navegador.

## Publicación gratuita

Puedes subir este proyecto a GitHub Pages, Netlify, Cloudflare Pages o Vercel como sitio estático. El archivo principal debe llamarse `index.html`.

## Notas de versión

- Plan diario por semana desde el 06 de julio de 2026.
- Registro de objetivos por día, horas reales, confianza y observaciones.
- Estados de temas: pendiente, parcial, cumplido, postergado/arrastre y adelantado.
- Posibilidad de postergar temas a la próxima sesión de la misma materia, al sábado o a la semana siguiente.
- Posibilidad de adelantar temas futuros de la misma materia.
- Exportación/importación JSON y exportación CSV.
- Corrección del error `ReferenceError: day is not defined` en la vista de plan diario.
- Validación de sintaxis JavaScript realizada con `node --check`.
