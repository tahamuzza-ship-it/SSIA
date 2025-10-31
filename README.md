# Tahamusha Dashboard Artes Marciales — clase 150 a 192

Dashboard estático que muestra la colección de clases (150 a 192) con visualizaciones y enlaces a los videos / recursos.

## Contenido del proyecto

- `index.html` — página principal del dashboard (usa D3.js / Chart.js para visualizar datos).
- `data/clase_150_a_192.csv` — datos en CSV con los campos: `class_number,title,url,platform,notes`.
- `assets/` — imágenes y recursos estáticos (ej. `assets/senseytao2.jpg`).
- `README.md` — este archivo.

## Cómo probar localmente (recomendado)

1. Abre una terminal en la carpeta raíz del proyecto.
2. Sirve el sitio por HTTP para evitar problemas con `file://`:

```bash
# Si tienes Python 3
python3 -m http.server 8000
# abre en el navegador:
http://localhost:8000/
