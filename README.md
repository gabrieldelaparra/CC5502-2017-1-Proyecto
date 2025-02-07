
# Geometría Computacional
#### <center>Gabriel De La Parra</center>

La propuesta inicial, es utilizar algoritmos de geometría en 2D para realizar procesamiento, análisis y extracción de features sobre distintas imágenes.

Específicamente, se <del>desea</del> *deseaba* procesar distintos símbolos de diagramas eléctricos y obtener distintas métricas para cada uno. Dichas métricas <del>pueden</del> *podrían haber* servir para realizar el reconocimiento y clasificación de los mismos en otros escenarios.

Se buscó un enfoque distinto pero dentro del mismo campo, el manejo de imágenes con algoritmos geométricos para análisis y extracción de features.

En este trabajo se utilizarán los diagramas de Voronoi &lt;informal&gt; para lo que todo el mundo conoce que hacen, pero nadie hace.&lt;/informal&gt; Se trabajará con la [API de Google Maps]() para encontrar lugares de interés y sus diagramas de [Voronoi]() con respecto a una dirección dada.

En una primera instancia se decidió ocupar [C++]() y [CGAL]() para lo anterior, sin embargo se optó finalmente por trabajar en [Python]() y [SymPy]().

CGAL es una librería muy poderosa, con diversas prestaciones y algoritmos en 2D y 3D. El autor considera que su instalación y uso es de mayor complejidad que otras opciones revisadas. De manera similar, al no tratarse de un escenario donde se requiere una alta capacidad computacional, no se justifica el uso de una librería tan compleja. 

Dado lo anterior, se utilizará Python como lenguaje, por su simplicidad y su facilidad de integración con otras plataformas, como [Jupyter Notebook](), [ipyWidgets]() y [mpld3](). Para los algoritmos geométricos se utilizará [Sympy](). 

Sympy es una librería para matemática simbólica, sin embargo tiene varios módulos de geometría. Entre estos se encuentran implementaciones para:
- Manejo de puntos, segmentos, polígonos
- Cálculo de áreas e interesecciones
- Cálculo de Cerradura Convexa (Convex Hull)
- Triangulaciones
- Diagramas de Voronoi
- Cálculo del camino más corto
