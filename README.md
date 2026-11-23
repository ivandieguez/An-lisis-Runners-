Análisis estadístico y simuladores interactivos de rendimiento en el Maratón de Boston
# Análisis Comparativo de Rendimiento: Maratón de Boston (Élite vs. Aficionados)

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivandieguez/An-lisis-Runners-/blob/main/Runners.ipynb)

Estudio exploratorio, estadístico y visual sobre el desempeño de **26.651 finalistas** del Maratón de Boston (`42,195 km`), contrastando la fisiología de carrera, la distribución etaria, las brechas de género y la composición internacional entre atletas **Élite** y **Aficionados**.


## Principales Hallazgos
1. **Diferencia estructural de ritmo:** El segmento Élite (0,62% del total, 166 atletas) mantiene un ritmo medio de **3:34 min/km** (`16,8 km/h`), mientras que el pelotón Aficionado (99,38%, 26.485 atletas) promedia **5:32 min/km** (`10,9 km/h`).
2. **Desfase temporal en ruta:** Al minuto 150 de carrera (`2:30:00`), más del **62% de la élite ya cruzó la meta**, mientras el corredor aficionado promedio recién transita el **kilómetro 27,1**.
3. **Curva etaria y resistencia:** En los aficionados, el ritmo promedio se mantiene estable entre los 18 y los 44 años (`~5:18` a `5:22 min/km`), comenzando un descenso gradual recién a partir de los 45 años.
4. **Composición internacional:** Delegaciones como **Kenia** y **Etiopía** presentan una altísima proporción de atletas élite (> 70%), mientras que países como **Estados Unidos**, **Canadá** y **Argentina** están compuestos casi en su totalidad (> 98%) por corredores aficionados.

---

## Estructura del Repositorio y Tecnologías
* `Runners.ipynb`: Notebook principal con el análisis completo, gráficos estadísticos y simuladores interactivos.
* `Dataset-Boston-2019.csv`: Base de datos de finalistas utilizada para el estudio.
* `LICENSE`: Licencia abierta **MIT**[cite: 3].
* **Herramientas:** Python (`pandas`, `numpy`, `matplotlib`) + HTML5/CSS3/JavaScript embebido.

# 🏃‍♂️ Análisis y Simulador Interactivo — Maratón de Boston 2019

Proyecto de análisis de datos sobre los resultados oficiales del **Maratón de Boston 2019** (`42,195 km`), que incluye un **simulador interactivo de carrera en pista** con animaciones en tiempo real, banderas oficiales de 78 países y comparación de rendimiento por delegación.

---

## 🎮 Probar el Simulador Interactivo en Vivo

> **Nota:** GitHub bloquea por seguridad la ejecución de JavaScript e `<iframe>` dentro de los archivos `.ipynb`. Podés interactuar con el simulador completo desde cualquiera de estos dos enlaces:

* **🚀 Abrir Simulador Web (GitHub Pages):**  
  👉 **[Hacé clic acá para correr la carrera en vivo](https://TU-USUARIO.github.io/TU-REPOSITORIO/simulador_boston_2019.html)**
* **📓 Ver Notebook Completo Interactivo (nbviewer):**  
  👉 **[Abrir Notebook con tablas y pista integrada](https://nbviewer.org/github/TU-USUARIO/TU-REPOSITORIO/blob/main/TU-NOTEBOOK.ipynb)**

### ¿Qué permite hacer el simulador?
* **Selección libre de 4 carriles:** Elegí tu país principal y 3 países rivales entre todas las delegaciones con al menos 10 finalistas.
* **Velocidades reales:** Cada corredor avanza según la velocidad promedio real registrada por su país en los 42,195 km.
* **Controles en tiempo real:** Botones de `▶ PLAY`, `⏸ PAUSA` y `↺ REINICIAR` con reloj cronometrado.
* **Podio y celebración:** Detección automática del primer puesto (`🥇 ¡GANADOR!`) con iluminación del carril vencedor y fuegos artificiales animados.

---

## 📊 Principales Hallazgos del Dataset

* **Cobertura:** Más de 26.000 corredores finalistas de más de 100 países analizados (`Dataset-Boston-2019.csv`).
* **Rendimiento por delegación:** Comparación de tiempos promedio, ritmos medios (`min/km`), velocidades (`km/h`), mejores marcas individuales y proporción de atletas élite (`< 2:30:00` en hombres y `< 2:50:00` en mujeres).
* **Duelos destacados:** Delegaciones europeas y africanas lideran los tiempos promedio más rápidos, mientras que Norteamérica concentra el mayor volumen de participación.

---

## 🛠️ Tecnologías Utilizadas

* **Python 3** (`pandas`, `numpy`) para limpieza, transformación y agregación de métricas atléticas.
* **HTML5 / CSS3 / JavaScript** embebido mediante `IPython.display` e `<iframe>` (`srcdoc`) para lograr compatibilidad total en entornos **JupyterLite** y navegadores web.

---

## 📁 Estructura del Repositorio

```text
├── Dataset-Boston-2019.csv       # Dataset original de resultados (separador ';')
├── simulador_boston_2019.html    # Aplicación web independiente del simulador
├── maraton_boston_2019.ipynb     # Notebook completo con análisis y código fuente
└── README.md                     # Documentación del proyecto
