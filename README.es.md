# Frontend Mentor – Solución al reto *Social Proof Section*

Esta es mi solución al desafío **Social Proof Section** de [Frontend Mentor](https://www.frontendmentor.io/).  
Este reto me permitió mejorar mis habilidades en **HTML y CSS** creando un diseño totalmente responsivo que presenta reseñas y calificaciones de usuarios con un estilo atractivo.

## Tabla de Contenido
- [Resumen](#resumen)  
- [El Reto](#el-reto)  
- [Diseño](#diseño)  
- [Enlaces](#enlaces)  
- [Mi Proceso](#mi-proceso)  
- [Construido Con](#construido-con)  
- [Lo Que Aprendí](#lo-que-aprendí)

## Resumen
Este proyecto es una **sección estática de landing page centrada en la prueba social**.  
El objetivo es mostrar la reputación positiva de un producto mediante:
- Un mensaje principal (hero)
- Bloques de calificación de distintas plataformas
- Testimonios de clientes con fotos de perfil

La interfaz presenta:
- Un diseño limpio y completamente adaptable  
- Jerarquía visual equilibrada entre texto, calificaciones y testimonios  
- Fondos diferentes para desktop y mobile que se ajustan automáticamente  
- Espaciado y tipografía consistentes para una lectura clara  

## El Reto
Los usuarios deben poder:

- Ver el diseño correctamente en **todos los tamaños de pantalla**  
- Leer claramente las calificaciones y los testimonios tanto en desktop como en mobile  

## Diseño
### Diseño Desktop  
![Desktop Design](./design/desktop-design.jpg)

### Diseño Mobile  
<img src="./design/mobile-design.jpg" width="200px" alt="Mobile layout">

## Enlaces
- **URL de la solución:** [Repositorio en GitHub](https://github.com/mlopezl/My-version-of-proof-section-master-challenge)  
- **URL del sitio en vivo:** [Demo en línea](https://mlopezl.github.io/My-version-of-proof-section-master-challenge/)  

## Mi Proceso
1. Comencé estructurando el layout usando **HTML semántico**, priorizando la legibilidad y accesibilidad.  
2. Utilicé **Flexbox** para posicionar los bloques principales: texto del encabezado, calificaciones y tarjetas de testimonios.  
3. Implementé un diseño completamente responsivo usando **media queries** y tamaños fluidos.  
4. Alterné **fondos entre desktop y mobile** según el ancho de pantalla.  
5. Estilicé los badges de calificación y las tarjetas de testimonios usando **variables CSS**, **tokens de espaciado** y valores consistentes de **border-radius**.  
6. Apliqué desplazamientos de layout usando `nth-child` para recrear la distribución escalonada de las tarjetas del diseño original.

## Construido Con
- HTML5  
- CSS3  
- Flexbox  
- Variables CSS  
- Diseño Responsivo (Media Queries)

## Lo Que Aprendí
- Cómo construir un **layout con precisión de diseño (pixel perfect)** usando las especificaciones como referencia.  
- Cómo organizar CSS siguiendo la metodología de nombres **BEM** para lograr escalabilidad.  
- Cómo posicionar elementos de forma responsiva usando desplazamientos con `nth-child`.  
- Cómo alternar **patrones de fondo entre desktop y mobile** usando media queries.  
- Cómo mantener armonía de espaciado con **gap**, **line-height** y **restricciones de max-width** consistentes.
