# 🧪 Laboratorio N.° 14 - Optimización y SEO

## 📚 Curso: Desarrollo de Aplicaciones Web Avanzado   
**Estudiante:** Rojas
**Fecha de entrega:**  hoy lunes 16 de junio

---

## 🎯 Objetivo

Optimizar el rendimiento y posicionamiento SEO de una aplicación web desarrollada con Next.js utilizando meta tags dinámicos, generación de sitemap y otras técnicas modernas de optimización.

---

## ⚙️ Herramientas utilizadas

- Next.js
- React.js
- Meta Tags Checker
- Google Search Console
- VS Code
- Navegador Chrome (para inspección de meta tags)
- Sistema operativo: Windows 11

---

## 🛠️ Pasos realizados

### 1. Instalación del Proyecto
```bash
npx create-next-app@latest mi-proyecto-seo
cd mi-proyecto-seo
npm install
npm run dev

## 🔍 Observaciones

> A continuación, se detallan las principales observaciones surgidas durante el desarrollo del laboratorio:

- ⚠️ **Generación del sitemap dinámico:** Se requirió investigar la estructura XML adecuada y cómo Next.js maneja los endpoints en `/api` para generar un sitemap válido.
- 🧪 **Validación de meta tags:** Al utilizar herramientas como Meta Tags Checker, se detectaron errores en la sintaxis de algunas etiquetas OG (`og:description` y `og:image`), los cuales fueron corregidos tras una revisión del código.
- 🖼️ **Carga de imágenes optimizadas:** Inicialmente, las imágenes no se renderizaban correctamente debido a una ubicación errónea en la carpeta `/public`. Este error se solucionó reorganizando los archivos.
- 🔄 **Archivo robots.txt y su impacto en SEO:** La validación del sitemap en Google Search Console no funcionaba hasta que se utilizó la URL exacta del entorno de despliegue. Se corrigió la ruta y se volvió a validar exitosamente.
- 🧠 **Curva de aprendizaje con `_app.js`:** La configuración global de fuentes y estilos generó confusión inicialmente, pero fue comprendida tras revisar la documentación oficial y hacer pruebas controladas.

---

## ✅ Conclusiones

> Reflexión crítica y técnica sobre el trabajo realizado:

- 🚀 **Aplicación real de técnicas SEO:** Este laboratorio facilitó el aprendizaje práctico de cómo mejorar la indexación de sitios en buscadores usando herramientas propias de Next.js, sin depender de plugins externos.
- 🛠️ **Resolución de problemas técnicos:** Las principales dudas se abordaron utilizando la documentación oficial y realizando pruebas iterativas, lo que fomentó un enfoque autodidacta para solucionar errores del código.
- 🧩 **Integración de funcionalidades modernas:** Se implementaron componentes clave como meta tags dinámicos, sitemap automático, lazy loading y optimización de imágenes y fuentes, todos fundamentales en aplicaciones web profesionales.
- 📈 **Mejora en la performance del sitio:** Gracias a estas prácticas, la aplicación ahora tiene mejor tiempo de carga, estructura semántica clara y mejor compatibilidad con herramientas de analítica y posicionamiento.
- 💡 **Valor agregado para futuros proyectos:** El conocimiento adquirido no solo es aplicable a este laboratorio, sino que representa una base sólida para implementar SEO técnico en proyectos reales de frontend.

---
