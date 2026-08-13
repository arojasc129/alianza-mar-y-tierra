# alianza-mar-y-tierra
Alianza Mar y Tiera sitio estatico

Originalmente creado en Webflow

## Cómo usar este proyecto

- **Requisitos:** Tener Ruby y Bundler instalados.
- **Instalar dependencias:**
```bash
gem install bundler   # si no tienes bundler instalado
bundle install
```
- **Previsualizar en local (desarrollo):**
```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml --livereload
```
O también:
```bash
rake serve
```
Abre http://127.0.0.1:4000 en tu navegador.

- **Construir para producción:**
```bash
JEKYLL_ENV=production bundle exec jekyll build
```
El sitio generado se encontrará en la carpeta `_site/`.

- **Notas rápidas:** el contenido principal está en las carpetas de nivel superior (por ejemplo `solutions/`, `newsroom/`), y los assets están en `css/`, `js/` e `images/`.