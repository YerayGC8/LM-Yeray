# Documentación UD1 Lenguajes de Marcas

## Introducción a Lenguajes de marcas

### Definición

Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas.

### Clasificación de Lenguajes de marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Dar formato a documentos de texto|HTML, CSS|
|Intercambio de información|Almacenar información de forma ordenada|XML, RSS|
|Documentación|Documentar proyectos|Markdown, Wikitext|

## Instalación y configuración del entorno

1. Instalamos [VS Code](https://code.visualstudio.com/)
2. Instalamos plugins
   - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  
  ![Logo de Markdown All in One](https://yzhang.gallerycdn.vsassets.io/extensions/yzhang/markdown-all-in-one/3.6.3/1741534224980/Microsoft.VisualStudio.Services.Icons.Default)
   - [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  
  ![Logo de HTML CSS Support](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUWFZzccVs8uCeiZLW8CqSYREkKTneHueiJ7mhTj4tPQ&s=10)
   - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
  
  ![Logo de Live Preview](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6GR7kJOGmRPDTkrWOYhd9flDyZLSxIObCOihP0GNNPA&s)
   - [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
  
  ![Logo de XML](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1rP-8uvzuZnsgUgCY_S9vNGJfdR0KAD3CeMDXpoZlpw&s=10)

  3. Instalamos Git
   ```bash
 sudo apt install git
   ```

  4. Configurar repositorio git (en la carpeta principal del proyecto)
   ```bash
   git init
   git add .
   git commit -m "Comentario descriptivo"
   ```
  ## Descripción de los plugins
   
   |Nombre|Imagen|Uso|
   |------|------|---|
   |Markdown All in One|![Logo de Markdown All in One](img/Markdown_All_in_One.png)|Visualizar los markdown formateados|
   |HTML CSS Support|![Logo de HTML CSS Support](img/HTML_CSS_Support.png)|Facilitar la sintaxis y el autocompletado del CSS|
   |Live Preview|![Logo de Live Preview](img/Live_Preview.png)|Visualizar los HTML formateados|
   |XML|![Logo de XML](img/XML.png)|Facilitar la sintaxis y el autocompletado de XML|