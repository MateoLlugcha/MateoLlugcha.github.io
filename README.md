# Angel Mateo Llugcha Rojas

https://www.figma.com/design/xsH4TEO9zuqpNv1xDImpQ3/Portafolio-Personal---Free-Template--Community-?node-id=0-1&m=dev&t=6ymo0BEmt6txh5qd-1


# Mejoras de Accesibilidad e Inclusión

Este sitio web ha sido ajustado para mejorar la experiencia de usuarios con discapacidades, aplicando principios de diseño inclusivo y accesibilidad web.

## Ajustes Realizados

### 1. Foco visible para navegación por teclado
Se implementó un estilo de enfoque (focus) personalizado en elementos interactivos como enlaces (`<a>`), botones (`<button>`) e inputs (`<input>`). Esto permite a los usuarios que navegan mediante teclado (por ejemplo, usando la tecla `Tab`) identificar claramente en qué elemento se encuentran.

**CSS aplicado:**
```css
a:focus, button:focus, input:focus {
  outline: 3px solid #00f;
  outline-offset: 2px;
}
