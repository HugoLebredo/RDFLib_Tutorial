# RDFLib Tutorial

![RDFLib logo](https://rdflib.readthedocs.io/en/stable/_static/RDFlib.png)

**RDFLib** es una librería de Python para trabajar con **RDF**. **RDFLib** contiene la mayoría de herramientas que se necesitan para trabajar con **RDF**. 

Incluye:

- *Parseadores* y *serializadores* para **RDF/XML**, **N3**, **NTriples**, **N-Quads**, **Turtle** y **JSON-LD** (via plugin).
- Una *interfaz gráfica* que puede ser respaldada por cualquiera de varias implementaciones de Store.
- Una implementación de **SPARQL 1.1**. Pemite declarar consultas en el grafo.

## Fuentes

- 📽 [Lista de videos](https://www.youtube.com/@yeshwanthreddy9242). Esta bien para empezar, explica como trabajar en Google Colab.
- 🎓 Sitio web de la asignatura [Knowledge graphs](https://wiki.app.uib.no/info216/index.php?title=INFO216_Wiki) de la universidad de Bergen. Toda la doc abierta.

## Instalación de RDFLib

Según sea el entorno en el que vamos a  trabajar utilizar el correspondiente comando para la instalación **RDFLib**.

```bash
# Instalación local
pip install rdflib 
# Instalación en Google Colab
!pip install rdflib 
# Instalación en Conda
conda install -c conda-forge rdflib 
```

Comprobar que la instalación ha sido exitosa.

```bash
# Instalación local
pip show rdflib
# Instalación Google Colab
!pip show rdflib
```