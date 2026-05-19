# 🧪 ACID ZONE PWA - Sistema de Pedidos y Geolocalización

Aplicación Web Progresiva (PWA) de alta fidelidad desarrollada para el negocio de frutas y gomitas **Acid Zone**, adaptando al 100% los valores, productos y dinámicas comerciales de su carta oficial.

## 🚀 Características Principales

- **Diseño Ultra Moderno:** Interfaz responsiva con temática Cyberpunk/Neón basada en tonos verde ácido (`#39ff14`) y púrpura eléctrico.
- **Formato PWA Nativo:** Totalmente instalable en dispositivos móviles y de escritorio mediante su archivo de manifiesto y Service Worker integrado, permitiendo su ejecución sin barras de navegador externas.
- **Geolocalización Inmediata:** Captura automática mediante el API de HTML5 de las coordenadas geográficas exactas del cliente, adjuntando de manera automatizada el enlace dinámico a Google Maps en el cuerpo del pedido.
- **Integración de Despacho por WhatsApp:** Genera un string completamente formateado en negritas y saltos de línea estructurados que calcula productos, adiciones y el costo de domicilio base ($3.000), enviándose de forma directa al número del negocio (`323 806 8384`).
- **Créditos Obligatorios de Marca:** Incluye pie de página legal e inalterable asignando los derechos de autoría y propiedad a nombre de **Vibras Positivas HM**.

## 📁 Arquitectura del Proyecto

El código fuente está modularizado en tres archivos clave para un despliegue sin configuraciones complejas:

1. `index.html`: Contiene la maquetación visual estructurada, los estilos CSS y los controladores dinámicos en JavaScript para el cálculo del carro de compras y la geolocalización satelital.
2. `manifest.json`: Archivo de metadatos de configuración que habilita el instalador nativo en Android, iOS y Chrome.
3. `sw.js`: Service Worker básico para almacenamiento en caché de fuentes y hojas de estilos externas, optimizando la velocidad de respuesta.

## 🔧 Instrucciones para Despliegue Directo

1. **Guardar los archivos:** Descarga o copia los bloques de código provistos a una misma carpeta en tu entorno local.
2. **Iconografía:** Añade dos imágenes en formato PNG con los nombres `icon-192.png` y `icon-512.png` en el mismo directorio raíz (estos servirán como los iconos de la app en la pantalla del celular).
3. **Servidor Seguro:** Sube los archivos a cualquier hosting estático gratuito compatible con protocolo SSL (HTTPS) como **Netlify** o **GitHub Pages**. *(Nota: El API de geolocalización del navegador exige obligatoriamente conexiones seguras HTTPS para poder capturar coordenadas).*
4. **Instalación:** Abre el link generado desde el navegador móvil de tu cliente y verás aparecer la barra o banner de instalación en la pantalla de inicio.

---
**Desarrollado y Distribuido bajo la Licencia de Propiedad Intelectual de:** **Hecha por VIBRAS POSITIVAS HM**
