# HD-sEMG y ELA · Revisión de alcance

Sitio científico de síntesis visual para el artículo **“HD-sEMG y descomposición de unidades motoras en la esclerosis lateral amiotrófica: revisión de alcance”**.

## Archivos

- `index.html`: estructura, contenido, gráficos SVG y enlaces de contacto.
- `style.css`: estilos adaptables a escritorio y móviles.

El sitio es estático y no necesita instalar dependencias.

## Vista local

1. Clona el repositorio y entra a la carpeta:

   ```bash
   git clone https://github.com/diegomcs/hdsemg-als-research.git
   cd hdsemg-als-research
   ```

2. Inicia un servidor local con Python:

   ```bash
   python -m http.server 8000
   ```

3. Abre [http://localhost:8000](http://localhost:8000) en el navegador. Para detener el servidor, vuelve a Git Bash y pulsa `Ctrl+C`.

También puedes abrir `index.html` directamente, aunque un servidor local se parece más al funcionamiento en Pages.

## Publicación en GitHub Pages

El sitio está preparado para servirse desde la raíz del repositorio. Para publicar cambios:

1. Guarda los archivos, crea un commit y súbelo a `main`:

   ```bash
   git add index.html style.css README.md
   git commit -m "Actualizar sitio de revisión HD-sEMG y ELA"
   git push origin main
   ```

2. En GitHub, abre **Settings → Pages**. Si la fuente es **Deploy from a branch**, selecciona `main` y la carpeta `/(root)`, y guarda.
3. En **Actions**, confirma que el flujo **pages-build-deployment** termina correctamente.
4. Abre el sitio publicado: https://diegomcs.github.io/hdsemg-als-research/

El botón **Solicitar artículo completo** abre un mensaje dirigido a los autores; no se publica el archivo Word ni se ofrece una descarga directa.

## Fuente de contenido

Las cifras del flujograma, la síntesis, las referencias seleccionadas y las propuestas futuras se tomaron del artículo fuente. Las interacciones usan HTML nativo y no requieren bibliotecas externas.
