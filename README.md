# Mayan Huipil Digital Art Generator

### Project Description
Developed a programmatic 2D graphic art canvas that replicates a traditional Mayan *huipil* (a uniquely designed indigenous blouse) using Java's native rendering capabilities. As my introductory project in Java, this application maps complex geometric shapes across a strict pixel-grid system to compile detailed, thematic sub-compositions. 

### Core Features & Technical Highlights

* **Programmatic Vector Scenes:** Engineered several highly detailed geometric objects completely from scratch using coordinate positioning math:
  * **Food Mechanics:** Formulated a cooking pan rendering logic using `Polygon` coordinate plotting, layered `fillOval` layers for eggs, and a textured burrito using `drawLine` sequences for grill marks.
  * **Physical Objects:** Implemented complex composite rendering for a pickleball paddle (`fillArc`), gym dumbbells (`fillRect`), and audio headphones using arc sweeps (`drawArc`).
  * **Linear Stroke Reduction:** Programmed a segmented fishing rod system that dynamically scales down structural width using consecutive `BasicStroke` variations from 10px down to 5px.
* **Custom RGB Color Engine:** Designed a custom color matrix to simulate rich, textile-like pigments, declaring explicit color instances such as `lineGreen`, `fishGreen`, `burrito`, `grill`, and `pickle`.
* **Diagnostic Grid Tool:** Built a custom math-based helper engine (`drawGrid`) using loops to calculate and render a dynamic 20-pixel interval graph with auto-rotating coordinate text strings for pixel alignment.

### Tech Stack & Architecture
* **Language:** Java (JDK Core)
* **Graphics Framework:** `java.awt.Graphics`, `java.awt.Graphics2D`, `java.awt.Color`, `java.awt.Polygon`
* **UI Windows:** `javax.swing.JFrame`, `javax.swing.JPanel` using custom `paintComponent` overrides
* **Software Architecture:** Object-Oriented Layout utilizing nested operational UI panels and standard canvas rendering lifecycles.

### How to Run the App
Ensure you have the Java Runtime Environment (JRE) installed on your computer.

1. Clone or download this repository.
2. Compile the source file:
   ```bash
   javac MyHuipil.java
