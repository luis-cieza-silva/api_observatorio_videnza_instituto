# API Observatorio Videnza Instituto

Guía práctica para consumir la API del Observatorio de Propuestas del Bicentenario.

## Contenido

- `Guia_Ejecucion_API_Observatorio.ipynb`: guía para ejecutar la función que consulta la API y extrae datos.
- `Manual_Codigos_API_Observatorio.md`: manual para obtener los códigos de series estadísticas.
- `image.png`, `image-1.png`, `image-2.png`: imágenes de apoyo del manual.

## Cómo proceder

1. Revisa `Manual_Codigos_API_Observatorio.md` para obtener el `codigo_serie` del gráfico que te interesa.
2. Abre `Guia_Ejecucion_API_Observatorio.ipynb` en Jupyter/VS Code.
3. Ejecuta las celdas en orden (instalación opcional, imports, función y ejecución básica).
4. Cambia el valor de `codigo_serie` y vuelve a ejecutar la celda de consulta.
5. Usa el DataFrame resultante (`df`) para análisis o exportación.
