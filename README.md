# LogiData — Dashboard de instancias (5, 10, 15 y 20 clientes)

Este proyecto contiene el dashboard Streamlit y los **resultados reales** facilitados para cuatro instancias.

## Cómo ejecutarlo localmente

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Al abrir, la barra lateral permite seleccionar la instancia. El dashboard detecta los archivos de `resultados_logidata/` y no requiere cargarlos manualmente ni ejecutar la heurística.

## Publicación en Streamlit Community Cloud

1. Subir los **contenidos de esta carpeta** a un repositorio de GitHub, manteniendo su estructura.
2. Crear la aplicación en https://share.streamlit.io/ con rama `main` y archivo principal `app.py`.
3. Abrir la URL publicada y elegir entre 5, 10, 15 y 20 clientes en el selector de instancias.

## Archivos

- `app.py`: código original del programa y dashboard, con detección de Streamlit, sin cambios en la heurística.
- `resultados_logidata/`: los cuatro consolidados completos, con los nombres que espera el selector.
- `respaldos_parciales/`: resultados parciales de FI/FII como respaldo; no sustituyen a los consolidados completos.
- `requirements.txt`: dependencias.

**Aviso:** el código compila y la estructura de resultados es compatible, pero no se ha ejecutado la interfaz Streamlit completa en este entorno. Verifica el arranque antes de compartir la URL. Si el repositorio es público, también lo serán los Excel.
