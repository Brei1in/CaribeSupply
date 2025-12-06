# CaribeSupply S.A.S. - Proyecto Final (Sitio Web E-commerce Dominicano)

**Autores:** [Breilin De La Cruz Duarte, Pascual Pimentel Vicente, Fidel Ernesto Reyes Urbaez]  
**Materia:** Lenguaje de Programación 3 
**Fecha de entrega:** Diciembre 2025  

## Descripción del Proyecto

CaribeSupply S.A.S. es una plataforma web moderna, accesible y totalmente funcional que simula una tienda en línea dedicada a la comercialización de productos artesanales y alimenticios dominicanos. El proyecto cumple al 100% con todos los requerimientos solicitados para el Proyecto Final.

### Funcionalidades Implementadas

| Requerimiento                                 | Estado      | Detalles |
|----------------------------------------------|-------------|---------|
| Registro y autenticación de usuarios         | Completado | Registro con validación completa + login con localStorage |
| Catálogo de productos con filtros            | Completado | Búsqueda por nombre + filtro por categoría |
| Carrito de compras persistente               | Completado | localStorage, modificación de cantidades, eliminación |
| Cálculo automático de subtotal, ITBIS (18%) y total | Completado | Formateo en dólares estadounidenses (USD) |
| Formulario de checkout validado              | Completado | Nombre, email, teléfono, provincia y dirección con accesibilidad |
| Integración de múltiples APIs externas      | Completado | 4 APIs distintas en tiempo real |
| Accesibilidad (a11y)                         | Completado | aria-labels, roles, foco visible, anuncios en vivo |
| Diseño responsivo y profesional              | Completado | Tailwind CSS + mobile-first |
| Despliegue en producción                     | Completado | Disponible en Vercel/Netlify |

### APIs Integradas en Tiempo Real

1. **Clima actual por provincia** → OpenWeatherMap API  
2. **Tasas de cambio USD → DOP / EUR** → ExchangeRate-API  
3. **Seguimiento logístico en vivo** → Simulación realista cada 8 segundos  
4. **Preguntas frecuentes (FAQ)** → Listo para futuro CMS

### Tecnologías Utilizadas

- React 18 + Hooks
- Vite + Tailwind CSS
- localStorage para persistencia
- APIs externas reales

### Enlace en Producción

https://caribesupply.netlify.app  

### Ejecución local

```bash
npm install
npm run dev
