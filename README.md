[README.md](https://github.com/user-attachments/files/34533477/README.md)
# Laboratorio Virtual de Métodos Numéricos 🧮

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

Plataforma educativa de código abierto diseñada para la visualización, experimentación y análisis de métodos matemáticos. Este proyecto ha sido estructurado conforme al Programa Analítico de Ingeniería en Computación de la **Universidad Autónoma de Zacatecas (UAZ)**.

## 🎯 Objetivo del Proyecto

Proporcionar a los estudiantes de ingeniería una herramienta interactiva que cierre la brecha entre la teoría matemática abstracta y su implementación computacional. La plataforma permite a los usuarios modificar funciones, alterar parámetros en tiempo real y observar el comportamiento de la convergencia y el error numérico mediante simulaciones gráficas.

## 🚀 Características Principales

*   **Renderizado Matemático en Tiempo Real:** Tipografía matemática de alta calidad impulsada por KaTeX.
*   **Análisis Dinámico:** Parseo y evaluación de ecuaciones ingresadas por el usuario utilizando Math.js.
*   **Visualización Científica:** Gráficos generados nativamente mediante HTML5 Canvas, mostrando curvas de funciones, áreas de integración, rectas tangentes/secantes y vectores de solución.
*   **Diseño Responsivo:** Interfaz moderna y adaptable a cualquier dispositivo móvil o de escritorio gracias a Tailwind CSS.
*   **Snippets de Código:** Cada módulo incluye su equivalente algorítmico vectorizado en Python o R para facilitar la transición a la programación.

## 📚 Módulos Disponibles

La suite de laboratorios está dividida en las siguientes unidades temáticas:

1.  **Raíces de Ecuaciones (`raices.html`)**
    *   *Métodos Cerrados:* Bisección y Falsa Posición.
    *   *Métodos Abiertos:* Newton-Raphson y Secante.
2.  **Sistemas de Ecuaciones Lineales (`lineales.html`)**
    *   *Directos:* Eliminación Gaussiana, Gauss-Jordan, Factorización LU (Doolittle).
    *   *Iterativos:* Gauss-Seidel.
3.  **Integración Numérica**
    *   Regla del Trapecio simple y de segmentos múltiples (`trapecio.html`).
    *   Reglas de Simpson 1/3 y 3/8 (`Simpson.html`).
    *   Extrapolación de Richardson y Método de Romberg (`Romberg.html`).
    *   Cuadratura Gaussiana / Fórmulas de Gauss-Legendre (`Cuadratura.html`).
4.  **Ecuaciones Diferenciales Ordinarias - EDO (`edo.html`)**
    *   Método de Euler (1er Orden).
    *   Familia RK2: Método de Heun, Mejorado del Polígono y Método de Ralston.
    *   Método de Runge-Kutta de 4to Orden (RK4).
5.  **Probabilidad y Estadística (`distribuciones_R.html`)**
    *   Modelado de distribuciones: Binomial, Poisson y Normal.
    *   Aproximación Normal mediante el Teorema del Límite Central.

## 🛠️ Tecnologías Utilizadas

El proyecto es estático (Client-side) y no requiere de un servidor backend, garantizando un despliegue rápido y alta seguridad.

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+).
*   **Estilos:** Tailwind CSS (v3 vía CDN).
*   **Matemáticas:** Math.js (v11), KaTeX (v0.16).
*   **Iconografía:** FontAwesome (v6.4).

## 💻 Instalación y Uso

Al ser una arquitectura de archivos estáticos, no se requiere la instalación de dependencias mediante `npm` o `pip`. 

**Para desarrollo local:**
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/metodos-numericos-uaz.git
   ```
2. Abre el archivo `index.html` directamente en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).

**Para acceso en línea:**
El proyecto está desplegado a través de GitHub Pages y puede ser accedido directamente desde cualquier navegador web en la siguiente ruta:
👉 [https://tiquis.github.io/metodos-numericos-uaz/] 

## 📄 Licencia

Este proyecto está distribuido bajo la licencia MIT. Eres libre de utilizarlo, modificarlo y distribuirlo con fines académicos y educativos.
