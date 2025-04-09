# Frontend Mentor - Social links profile solution

Esta es mi solución al reto [Social links profile challenge en Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Este tipo de retos me ayudan a practicar HTML semántico, SCSS, diseño responsivo y accesibilidad básica.

## Tabla de contenidos

- [Resumen](#resumen)
  - [El reto](#el-reto)
  - [Captura de pantalla](#captura-de-pantalla)
  - [Enlaces](#enlaces)
- [Mi proceso](#mi-proceso)
  - [Tecnologías usadas](#tecnologías-usadas)
  - [Lo que aprendí](#lo-que-aprendí)
  - [En qué quiero seguir trabajando](#en-qué-quiero-seguir-trabajando)
  - [Recursos útiles](#recursos-útiles)
- [Autora](#autora)

---

## Resumen

### El reto

Los usuarios deben poder:

- Ver los estados `hover` y `focus` para todos los elementos interactivos de la página.
- Visualizar el contenido centrado y adaptado a pantallas pequeñas.

### Captura de pantalla

![Captura de pantalla del reto](./screenshot.jpg)

### Enlaces

- [Solución en Frontend Mentor](https://your-solution-url.com)
- [Sitio en vivo](https://your-live-site-url.com)

---

## Mi proceso

### Tecnologías usadas

- HTML5 semántico  
- SCSS con variables  
- Flexbox  
- Mobile-first workflow  

### Lo que aprendí

- Cómo usar variables SCSS para mantener un esquema de colores consistente.
- Cómo centrar una tarjeta con Flexbox dentro del `body`.
- Cómo organizar los estilos por componentes (`.container`, `.card`, `.profile-image`, `.social-links-container`).
- Cómo manejar correctamente los `:hover` y `:focus` con buena accesibilidad visual.

#### Fragmento de SCSS representativo

```scss
.social-links-container a {
  color: $light-text-color;
  background-color: $dark-text-color;
  padding: 0.75rem;
  border-radius: 0.5rem;
  transition: background-color 0.3s;

  &:hover,
  &:focus {
    background-color: darken($dark-text-color, 10%);
  }
}
```

### En qué quiero seguir trabajando

- Seguir aplicando buenas prácticas de accesibilidad.
- Profundizar en cómo mejorar la estructura de carpetas en proyectos con SCSS.
- Trabajar con layouts más complejos usando CSS Grid.

### Recursos útiles

- [Frontend Mentor Docs](https://www.frontendmentor.io/resources)
- [Guía de SCSS (Sass)](https://sass-lang.com/guide)
- [Checklist de accesibilidad WCAG (nivel A/AA)](https://www.wuhcag.com/wcag-checklist/)

---

## Autora

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [@yourusername](https://github.com/yourusername)
