# 🧩 Responsive Login Template — Grid + Media Queries

Este proyecto es una práctica básica de **CSS Grid** y **Media Queries**, cuyo objetivo fue diseñar una interfaz de **login responsive**.  
El template adapta su diseño según el tamaño de la pantalla, mostrando una sección lateral adicional en pantallas grandes y una vista simplificada en dispositivos móviles.

---

## 🖼️ Vista general

El proyecto incluye:
- Un archivo HTML que define la estructura base del login.
- Un archivo CSS que implementa el diseño mediante **Grid Layout**.
- Una **media query** que modifica la distribución y visibilidad de los elementos a partir de los **1180px** de ancho.

---

## 🧱 Tecnologías utilizadas

- **HTML5**
- **CSS3 (Grid Layout, Media Queries)**
- **Font Awesome 7.0.1** (para íconos visuales)

---

## 📁 Estructura del proyecto

```bash
responsive_LoginTemplate/
│
├── responsive_login.html
└── css/
    └── newLogin_style.css
```

## 💡 Descripción del diseño

### 📱 Vista móvil
- El login se centra en la pantalla.
- La sección lateral (`.left-hidden-section`) permanece oculta.
- Los elementos se apilan verticalmente con espaciados simples.

### 💻 Vista escritorio
- El layout se divide en **dos columnas**:  
  - Izquierda: una sección de color azul con el texto *AdminExpress*.  
  - Derecha: el formulario de inicio de sesión.
- Se ajustan los tamaños de fuente, márgenes y botones.

---

## 📐 Media Query aplicada

```css
@media (min-width: 1180px) {
  body {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

  .left-hidden-section {
    display: flex;
    background: #3498db;
    align-items: center;
    justify-content: center;
  }
}
```

---

## 🚀 Instalación y ejecución local

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/Vik-tor39/responsive_LoginTemplate.git
cd responsive_LoginTemplate
```

### 2️⃣ Abre el archivo "responsive_login.html" en tu navegador

---

## 🧠 Aprendizajes
Durante esta práctica se aplicaron conceptos de:
- Diseño responsive usando media queries.
- Maquetación moderna con CSS Grid Layout.
- Ajuste dinámico de fuentes, márgenes y elementos visuales.

---

## 🏷️ Autor
**Víctor Suquilanda (Estudiante) | Ing. Software**  
Primera práctica con CSS Grid y Media Queries