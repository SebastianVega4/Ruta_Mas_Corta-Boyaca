# 🗺️ Ruta Más Corta - Boyacá

Este proyecto académico implementa el algoritmo de Dijkstra para hallar la ruta más corta entre distintos pueblos del departamento de Boyacá, Colombia. La interfaz gráfica, desarrollada en Java mediante la librería Swing, permite al usuario interactuar con un mapa visual del departamento, seleccionando puntos de origen y destino para obtener el camino óptimo. Esta herramienta se ha concebido como parte del proceso formativo en estructuras de datos y algoritmos aplicados a problemas del mundo real.

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

### 🚀 Instrucciones de Ejecución

1. Clonar el repositorio:
```bash
git clone https://github.com/sebasvega321/Ruta_Mas_Corta-Boyaca.git
```

3. Importar el proyecto en un IDE como **IntelliJ IDEA** o **Eclipse**.
4. Ejecutar la clase `App.java` que contiene el método `main()`.
5. Interactuar con la interfaz seleccionando el punto de partida y de llegada.

### 🏆 Contribución Académica

Este trabajo permite a los estudiantes:

- Comprender y aplicar el algoritmo de Dijkstra en escenarios reales.
- Integrar conceptos de estructuras de datos con componentes gráficos interactivos.
- Fortalecer habilidades en programación orientada a objetos y desarrollo de interfaces gráficas en Java.


## 👨‍🎓 Autor

Desarrollado por **Sebastián Vega**  
📧 *Sebastian.vegar2015@gmail.com*  
🔗 [LinkedIn - Johan Sebastián Vega Ruiz](https://www.linkedin.com/in/johan-sebastian-vega-ruiz-b1292011b/)

---

© 2023 — Universidad Pedagógica y Tecnológica de Colombia (UPTC)  
Facultad de Ingeniería — Ingeniería de Sistemas
