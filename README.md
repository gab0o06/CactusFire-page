# 🌵 CactusFire - Responsive Landing Page (Pure CSS & HTML)

Una página de aterrizaje (*Landing Page*) moderna y completamente responsiva, diseñada desde cero utilizando únicamente tecnologías web nativas. Este proyecto se enfocó en lograr una estructura semántica impecable, una estética visual limpia y una adaptación fluida a cualquier tamaño de pantalla mediante técnicas avanzadas de maquetación.

🎯 **Demo en Vivo:** [Visita el sitio desplegado](https://gab0o06.github.io/CactusFire-page/)

---

## 🛠️ Stack Tecnológico

* **Estructura:** HTML5 Semántico
* **Estilos:** CSS3 Puro (Flexbox & CSS Grid)
* **Metodología:** Enfoque en diseño fluido y adaptabilidad sin frameworks

---

## 🚀 Características Clave y Desafíos Técnicos

* **Maquetación Híbrida (Grid + Flexbox):** Uso estratégico de `CSS Grid` para la cuadrícula principal de secciones complejas (como las galerías de productos o cuadrículas de características) y `Flexbox` para la alineación interna de componentes de UI de forma flexible.
* **Diseño Fluido y Adaptable:** Implementación de unidades relativas (`rem`, `em`, `%`, `vw`, `vh`) para asegurar que el escalado de tipografías y contenedores sea proporcional y armónico en todas las resoluciones.
* **Cero Dependencias:** Desarrollo absoluto en CSS nativo, demostrando un entendimiento profundo del modelo de caja (*Box Model*) y de la cascada del navegador sin el peso adicional de frameworks como Bootstrap o Tailwind.
* **Arquitectura de Navegación:** Estructuración de barras de navegación semánticas y adaptadas para flujos de conversión de cara al usuario.

---

## 📐 Criterio de Ingeniería y Estructura

El desarrollo se centró en escribir código limpio, legible y escalable, aplicando buenas prácticas de maquetación en la industria.

### HTML Semántico para SEO y Accesibilidad
En lugar de estructurar el sitio con contenedores genéricos (`div-soup`), se utilizaron etiquetas semánticas de HTML5 para definir claramente las regiones de la página, mejorando el indexado en buscadores (SEO) y la compatibilidad con lectores de pantalla:

```html
<header>
  </header>

<main>
  <section class="hero">...</section>
  <section class="features">...</section>
</main>

<footer>
  </footer>
```
### Organización del Diseño con CSS Grid
Para resolver la distribución asimétrica de las tarjetas informativas de manera limpia, se implementó un sistema de rejilla bidimensional nativo, evitando el uso de márgenes forzados o posicionamientos absolutos:

```css
.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}
```
### Como ejecutar el proyecto Local
1. Clona el repositorio
```console
git clone [https://github.com/gab0o06/CactusFire-page.git](https://github.com/gab0o06/CactusFire-page.git)
```
3. Abre el archivo index.html
Puedes usar Live Server de VS code para un desarrollo en tiempo real.  
