## Bienvenidos 

You can use the [editor on GitHub](https://github.com/dordonez-ute-apdist/dordonez-ute-apdist.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dordonez-ute-apdist/dordonez-ute-apdist.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Java Streams 
Las Java Streams son lo que técnicamente, en programación funcional, se llama mónadas, que puesto de manera simple, son un tipo de objeto que contiene una serie de datos y que puede ser combinado en un flujo de procesamiento tipo pipeline: los datos pasan por una serie de procesos que piden transformarlos en cada paso, emitiendo nuevos datos, hasta lograr un dato o serie de datos final.

<br>
  <img src= Imágenes/1.jpg>
<br>

Un Stream, entonces, generalmente contiene una serie de elementos, que puede generarse, por ejemplo, a partir de una colección:
 
⦁	Los Stream tienen operaciones intermedias, que devuelven una nueva Stream transformada, que se puede seguir encadenando, pero que solo se ejecutan cuando en el pipeline existe una operación terminal. También tienen operaciones terminales, que cierran el pipeline y devuelven un valor que ya no es una Stream (o no devuelven nada), cerrando el pipeline.
⦁	Las Stream pueden ser seriales o paralelas. Aquellas seriales se procesaran en un solo hilo, y aquellas paralelas se procesaran en varios hilos, de manera automática, gracias al uso de ForkJoinPool del sistema. 
Operaciones Intermedias y Terminales:
Las operaciones intermedias son aquellas que devuelven un Stream transformada y las terminales cierran el pipeline. 
 
### Nota: Las Stream no se pueden reutilizar para evitar cualquier tipo de error. 
Operaciones Relevantes:


-	Filter(P) (Operación Intermedia)
-	Map(F) (Operación Intermedia)
-	ForEach(A) (Operación Terminal)
-	Sorted() (Operación Intermedia)
-	Reduce(I, O) (Operación Terminal)
-	Collect(C) (Operación Terminal)


