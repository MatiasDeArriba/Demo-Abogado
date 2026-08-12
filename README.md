# ⚖️ Estudio Jurídico — Sitio Web Institucional

Repositorio del sitio web institucional para estudio de abogados / profesional independiente. Desarrollado con tecnologías web puras (**HTML5, CSS3 y JavaScript vanilla**), priorizando rendimiento, SEO local, accesibilidad y conversión directa de clientes.
![Vista Previa del Sitio Web](Screenshots/CapturaWeb.png)

---

## 📌 Tabla de Contenidos

1. [Visión General del Proyecto](#-visión-general-del-proyecto)
2. [Estructura de Archivos](#-estructura-de-archivos)
3. [Requisitos y Stack Tecnológico](#-requisitos-y-stack-tecnológico)
4. [Instalación y Uso Local](#-instalación-y-uso-local)
5. [Estrategia de Frontend y UX/UI](#-estrategia-de-frontend-y-uxui)
6. [Integración del Formulario de Contacto (Backend Serverless)](#-integración-del-formulario-de-contacto-backend-serverless)
7. [Optimizaciones SEO y Metadatos](#-optimizaciones-seo-y-metadatos)
8. [Despliegue / Hosting](#-despliegue--hosting)

---

## 🎯 Visión General del Proyecto

El objetivo principal es brindar una presencia digital seria, sólida y confiable que convierta visitantes en clientes. 

### Principales Objetivos:
* **Generar Confianza:** Destacar número de matrícula profesional, colegio de abogados y trayectoria desde la portada (*Hero section*).
* **Fácil Contacto:** Integración con botón flotante de WhatsApp y formulario directo.
* **SEO Local:** Marcado de datos estructurados (`Schema.org / LegalService`) para mejorar visibilidad en Google Search y Maps.
* **Carga Ultrarrápida:** Arquitectura multipágina (MPA) estática sin dependencias pesadas ni frameworks superfluos.

---

## 📁 Estructura de Archivos

```text
Demo-Abogado/
├── index.html              # Página principal (Hero, Servicios, Sobre mí, CTA)
├── areas-de-practica.html  # Detalle completo de servicios jurídicos
├── sobre-nosotros.html     # Trayectoria, equipo, matrícula y colegiación
├── contacto.html           # Formulario principal, mapa y vías de contacto
├── blog/
│   └── articulo-1.html     # Artículos educativos y guía de dudas frecuentes
├── css/
│   ├── reset.css           # Normalización de estilos base entre navegadores
│   └── styles.css          # Variables globales, layout y componentes
├── js/
│   └── main.js             # Menú mobile, validación de forms y animaciones
├── img/
│   └── (imágenes)          # Fotografías e íconos en formato WebP optimizado
└── legal/
    ├── privacidad.html     # Política de Privacidad (cumplimiento Ley 25.326)
    └── terminos.html        # Términos y Condiciones / Aviso Legal
