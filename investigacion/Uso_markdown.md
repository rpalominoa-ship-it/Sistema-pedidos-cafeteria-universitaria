
# ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero creado por John Gruber en 2004. Se utiliza para aplicar formato a texto sin formato. Su objetivo es que el texto fuente sea lo más fácil de leer y escribir posible, incluso sin ser renderizado.

##### ¿Por qué se usa en Proyectos de Software?
Markdown es el estándar de facto en el desarrollo de software por varias razones clave:

1. Legibilidad y Simplicidad
El código fuente de un archivo Markdown (.md) es inherentemente legible. Esto es crucial para la documentación de software, donde la claridad inmediata es más importante que los gráficos complejos o el formato sofisticado. Los desarrolladores pueden leer y modificar los documentos sin necesidad de una herramienta de vista previa.

2. Control de Versiones (Git)
Los archivos Markdown son archivos de texto sin formato. Esto los hace perfectos para sistemas de control de versiones como Git. Los cambios (o diffs) entre dos versiones de un documento son muy fáciles de rastrear y revisar, ya que Git solo tiene que comparar líneas de texto simple, a diferencia de los formatos binarios como los documentos de Word.

3. Documentación Estándar (README)
El archivo más común en casi todos los proyectos de software, el README.md, se escribe en Markdown. Este archivo actúa como la puerta de entrada al proyecto, conteniendo información esencial como:

      - Una descripción del proyecto.

     - Instrucciones de instalación.

     - Guías de uso.

4. Soporte Universal
Plataformas de desarrollo populares como GitHub, GitLab, Bitbucket, y la mayoría de los generadores de documentación (como Jekyll o Hugo) y wikis renderizan Markdown de forma nativa. Esto asegura que la documentación se verá bien y será consistente sin importar dónde esté alojado el proyecto.

5. Facilidad para Escribir Código
Markdown tiene una sintaxis muy simple para formatear y resaltar bloques de código, lo cual es vital para los manuales técnicos y las guías de API.

# ¿Por qué se utiliza en proyectos de software?
|Razón	|Descripción|
|-------|-----------|
|Simplicidad|	Sintaxis intuitiva que no interrumpe el flujo de escritura|
|Legibilidad|	Los archivos son legibles incluso en formato plano|
|Universalidad|Soporte en GitHub, GitLab, editores de código y herramientas de documentación|
|Control de versiones	|Ideal para trabajar con Git ya que muestra diferencias claras
Colaboración	|Fácil de aprender para todos los miembros del equipo|

# EJEMPLOS PRACTICOS

# Encabezado H1
## Encabezado H2
### Encabezado H3
#### Encabezado H4

# LISTAS

- Elemento de lista
- Otro elemento
  - Subelemento
  - Otro subelemento
* Alternativa con asterisco
  
1. Primer elemento
2. Segundo elemento
3. Tercer elemento

# TABLAS
| Tecnología | Popularidad | Uso |
|------------|-------------|-----|
| JavaScript | ⭐⭐⭐⭐⭐ | Frontend y Backend |
| Python | ⭐⭐⭐⭐ | Data Science, IA |
| Go | ⭐⭐⭐ | Sistemas, APIs |



# IMAGENES Y ENLACES


<!-- Enlace con título -->
[Documentación Markdown](https://guides.github.com/features/mastering-markdown/ "Guía oficial")
<!-- Imagen -->
<img src="https://markdown-here.com/img/icon256.png" alt="Logo Markdown" width="100px" />


###### Imagen con enlace 
<!-- Enlace simple -->
[GitHub](https://github.com)
<!-- Imagen con enlace -->
<a href="https://github.com">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" width="120" />
</a>
  
## Ventajas de Markdown + GitHub
#####  Integración Nativa

- README automático: GitHub reconoce automáticamente README.md

- Visualización directa: Los archivos .md se renderizan automáticamente

- GitHub Pages: Generación de sitios web estáticos desde repositorios Markdown

- GitHub Wiki: Wikis completas usando solo Markdown