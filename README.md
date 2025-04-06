# 🗺️ Ruta Más Corta - Boyacá

Este proyecto académico implementa el algoritmo de Dijkstra para hallar la ruta más corta entre distintos pueblos del departamento de Boyacá, Colombia. La interfaz gráfica, desarrollada en Java mediante la librería Swing, permite al usuario interactuar con un mapa visual del departamento, seleccionando puntos de origen y destino para obtener el camino óptimo. Esta herramienta se ha concebido como parte del proceso formativo en estructuras de datos y algoritmos aplicados a problemas del mundo real.

### 📚 Contexto Académico

Este trabajo fue desarrollado como parte de la formación en Ingeniería de Sistemas, dentro del área de algoritmos y estructuras de datos avanzadas. El proyecto tiene como objetivo aplicar conocimientos teóricos en un caso práctico con impacto regional, utilizando herramientas gráficas y programación orientada a objetos.

### 🧠 Algoritmo Implementado

El algoritmo de **Dijkstra**, conocido por su eficiencia en la búsqueda de caminos más cortos en grafos ponderados y dirigidos, ha sido seleccionado para este caso debido a su idoneidad en contextos de rutas geográficas. El grafo representa los pueblos como nodos y las vías entre ellos como aristas con pesos correspondientes a la distancia entre localidades.

### 💻 Tecnologías Utilizadas

- **Lenguaje de programación:** Java
- **Interfaz gráfica:** Swing (`JFrame`, `JPanel`)
- **Representación gráfica del grafo:** Mapa interactivo personalizado con imágenes
- **Estructuras de datos:** Listas de adyacencia, colas de prioridad (implementadas manualmente)

### 🖼️ Visualización del Proyecto

El sistema permite:

- Visualizar el mapa de Boyacá con los pueblos conectados mediante rutas posibles.
- Seleccionar un punto de origen y uno de destino desde una lista desplegable.
- Calcular y visualizar la ruta más corta utilizando el algoritmo de Dijkstra.
- Mostrar el recorrido resaltado gráficamente en el mapa (con imágenes adjuntas).

<div align="center">
  <img src="./capturas/mapa_boyaca_1.jpg" alt="Ruta más corta - Panel principal" width="500"/>
  <img src="./capturas/mapa_boyaca_2.jpg" alt="Ruta más corta - Trayecto resaltado" width="500"/>
</div>

### 📂 Estructura del Repositorio

Ruta_Mas_Corta-Boyaca/
│
├── src/                     # Código fuente del proyecto
│   ├── App.java             # Clase principal con método main
│   ├── Dijkstra.java        # Implementación del algoritmo
│   ├── Grafo.java           # Lógica de nodos y aristas
│   └── UI/                  # Interfaz gráfica (JFrame, JPanel, etc.)
│
├── capturas/                # Imágenes de la aplicación en ejecución
│
├── README.md                # Documentación del proyecto
└── .gitignore               # Archivos y carpetas excluidas del control de versiones


### 📐 Modelo Matemático

Sea un grafo ponderado dirigido **G = (V, E)**, donde **V** representa los pueblos de Boyacá y **E** las vías entre ellos con una función de peso **w(u, v)** que indica la distancia entre los nodos. El algoritmo de Dijkstra busca minimizar la función de costo total **d(v)** para todo **v ∈ V**, calculando el valor más bajo posible de la suma de pesos desde el nodo fuente **s** hasta **v**.

La solución tiene una complejidad computacional de **O((V + E) log V)** al usar una cola de prioridad con estructura de montículo.

### 🚀 Instrucciones de Ejecución

1. Clonar el repositorio:
'''bash
git clone https://github.com/sebasvega321/Ruta_Mas_Corta-Boyaca.git
'''

2. Importar el proyecto en un IDE como **IntelliJ IDEA** o **Eclipse**.
3. Ejecutar la clase `App.java` que contiene el método `main()`.
4. Interactuar con la interfaz seleccionando el punto de partida y de llegada.

### 🏆 Contribución Académica

Este trabajo permite a los estudiantes:

- Comprender y aplicar el algoritmo de Dijkstra en escenarios reales.
- Integrar conceptos de estructuras de datos con componentes gráficos interactivos.
- Fortalecer habilidades en programación orientada a objetos y desarrollo de interfaces gráficas en Java.

### 📬 Contacto

Proyecto desarrollado por **Sebastián Vega**  
Estudiante de Ingeniería de Sistemas  
Universidad [Nombre de la Universidad]  
Contacto: [correo electrónico o redes académicas]
