# An-lisis-Runners-
Análisis estadístico y simuladores interactivos de rendimiento en el Maratón de Boston
# Análisis Comparativo de Rendimiento: Maratón de Boston (Élite vs. Aficionados)

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivandieguez/An-lisis-Runners-/blob/main/Runners.ipynb)

Estudio exploratorio, estadístico y visual sobre el desempeño de **26.651 finalistas** del Maratón de Boston (`42,195 km`), contrastando la fisiología de carrera, la distribución etaria, las brechas de género y la composición internacional entre atletas **Élite** y **Aficionados**.

---

## Simuladores Interactivos

> **Nota sobre interactividad:** El visor web de GitHub bloquea la ejecución de JavaScript por políticas de seguridad. Para interactuar en vivo con ambos simuladores, abrí el notebook haciendo clic en el botón azul de **Google Colab** arriba (o ejecutalo localmente en Jupyter).

[PEGAR_ACA_FOTO_SIMULADORES]

---

## Tablero Analítico Integral (8 Dimensiones)

### Distribución de Ritmo, Estructura Etaria y Evolución por Edad (Gráficos A - D)
[PEGAR_ACA_FOTO_GRAFICOS_1_A_4]

### Velocidad Media, Curva Acumulada (ECDF), Brecha de Género y Composición por País (Gráficos E - H)
[PEGAR_ACA_FOTO_GRAFICOS_5_A_8]

---

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
