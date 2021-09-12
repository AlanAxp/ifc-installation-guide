# Instalacion de Python y Julia en Jupyter Notebook

## Jupyter notebook 
 
Es una herramienta muy útil que nos permite ejecutar python, julia, R, y otros lenguajes de programación de forma interactiva desde un navegador de internet.  Además que nos permite manejar texto con formato, visualizar las gráficas y el código de una forma un poco mas intuitiva.
 
Para su instalación: 
 
* Windows y Mac (Usaremos el cliente de Anaconda por facilidad)

Deben descargar anaconda desde su [sitio oficial](https://www.anaconda.com/distribution/).
Esta vendrá con un instalador según su SO y dado que son usuarios expertos de cada sistema, seguro lo harán sin problemas.

Nota: Anaconda es un programa pesado, si su computadora cuenta con recursos un poco mas limitados, se recomienda usar *miniconda*
 
* Linux

Es mucho más sencillo ya que sólo deberán asegurarse que tengan instalado python 3+. Para revisar su versión de Python en la terminal deberán escribir:

```bash
python  --version
```
Y si no tienen la version 3+ podrán descargarlo [aqui](https://www.python.org). Una vez que lo tengan instalado, en su terminal deberán escribir:

```bash
pip install jupyter
```
Nota: 3+ es solo referencia a cualquier version de python3 (.7, .8 o .9)

Si esto solo les instala Jupyter con Python 2 deberán escribir `pip3` en lugar de `pip`.
 
 
Nota: Tanto en windows como en mac se puede instalar Jupyter sin la necesidad de Anaconda, lo cual es mejor ya que Anaconda no es un programa ligero.
Sin embargo la instalación es sólo un poco más complicada, además, Anaconda ya viene con varias librerías instaladas de Python. Si se desea, se puede hacer sin Anaconda (miniconda).
 
 
## Julia Language
 
Julia a diferencia de python, no es un lenguaje interpretado, es "compilado", precisamente Julia usa un compilador Just In Time (JIT) al que se hace referencia como "Just Ahead Of Time" (JAOT) en la comunidad , ya que Julia compila todo el código (por defecto) en código de máquina antes de ejecutarlo, lo que lo hace mucho mas veloz y eficiente que python. Sin embargo, al igual que python, mantiene una sintaxis muy cómoda y simple.

Julia deberá ser descargado de su [página oficial](https://julialang.org) y una vez que ya tengan Jupyter notebook instalado, podrán añadirlo al notebook con las siguientes instrucciones

### Windows y mac

1. Abrir la terminal de julia
2. Escribir en consola:

    ```julia
    using Pkg
    ```
    
3. Finalmente escribir: 

    ```julia
    Pkg.add("IJulia")
    ```
    
### Ubuntu

Les recomiendo seguir algún video tutorial en youtube en lo que encuentro el tiempo para escribir este apartado :v .
//TODO: Escribir este apartado
 


## Google Colaboratory
 
Es una herramienta de google para poder crear y ejecutar notebooks de python sin la necesidad de tener instalado jupyter o python en tu ordenador. Sin embargo esto mismo es un contra a su favor, ya que se depende enteramente de la conexión que tengas a internet.

Para poder usarlo basta con googlear “Google Colab” y entrar con su cuenta de google, que en este caso sería la de ciencias.
 



## Iniciar un Notebook

### Windows
En el prompt de Anaconda ejecutar 

```bash
jupyter notebook
```

### Ubuntu y Mac

Abrir cualquier terminal y escribir

```
jupyter notebook
```

Fin.
