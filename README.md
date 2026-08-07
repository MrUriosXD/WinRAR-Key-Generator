# WinRAR Key Generator 🛠️

Una aplicación web moderna, premium y completamente interactiva diseñada para la simulación, generación, copia y descarga local de archivos de licencia `rarreg.key` con fines estrictamente educativos y pruebas de concepto en entornos de aprendizaje[cite: 2].

---

## 🚀 Características Clave

- **🌐 Internacionalización Nativa (i18n):** Soporte completo para 9 idiomas (Español, English, Français, Deutsch, Italiano, Português, Русский, 简体中文, 日本語) con un selector personalizado de banderas y detección inteligente del idioma del sistema operativo[cite: 2].
- **🌓 Sistema de Temas Dinámicos:** Conmutador integrado que alterna de forma fluida entre Modo Oscuro (por defecto) y Modo Claro, adaptando los esquemas de color (`data-theme="light"`) y almacenando la preferencia en el `localStorage` del navegador[cite: 2].
- **🔒 Privacidad Absoluta (Serverless & Client-Side):** Procesamiento local en tiempo de ejecución impulsado por JavaScript puro. Los datos ingresados jamás se transmiten a servidores externos ni requieren bases de datos[cite: 2].
- **⚡ Interfaz de Usuario Avanzada:** Estética moderna basada en variables CSS centralizadas (`:root`), efectos de desenfoque de fondo (*glassmorphism*), diseño adaptivo móvil (*Mobile First*) y retroalimentación interactiva[cite: 2].
- **📊 Validación y Contadores en Tiempo Real:** Cuenta con indicadores de caracteres dinámicos que cambian a estado de advertencia visual al aproximarse a los límites permitidos (30 caracteres para usuario y 50 para licencia)[cite: 2].
- **📋 Copia Inteligente y Descarga ANSI:** Botón flotante animado para copiar el bloque de llaves con un solo clic al portapapeles y un sistema de empaquetado blob estructurado en codificación compatible `windows-1252` (ANSI)[cite: 2].

---

## 📖 ¿Qué es WinRAR?

**WinRAR** es una de las herramientas de compresión y descompresión de datos más potentes y utilizadas del mundo, desarrollada por Eugene Roshal[cite: 2]. Permite gestionar archivos en múltiples formatos (RAR, ZIP, entre otros) de manera rápida y eficiente, optimizando el espacio de almacenamiento[cite: 2]. 

> ⚠ **Aviso de Uso Educativo:** Esta herramienta ha sido diseñada exclusivamente con propósitos académicos y de investigación. Su objetivo es ilustrar a estudiantes de programación y administradores de sistemas la lógica de integración de archivos de registro internos, validación del DOM y flujos de internacionalización en aplicaciones web estáticas[cite: 2]. Para entornos comerciales y uso legítimo, se debe adquirir una licencia oficial a través de los canales autorizados[cite: 2].

---

## 🏷️ Tipos de Licencia Soportados

La aplicación cuenta con una cuadrícula interactiva que permite preseleccionar plantillas de licenciamiento estándar con un comportamiento de alternancia (*toggle*), o bien escribir un formato personalizado[cite: 2]:

* `Single User License` (1 PC) — *Cargada de forma predeterminada*[cite: 2]
* `Multi User Volume Licenses` (2–999 PCs)[cite: 2]
* `License for 1000 PCs or more` (1000+ PCs)[cite: 2]
* `Local Site License` (Local Site)[cite: 2]
* `Worldwide Unlimited Corporate License` (Global Corporate)[cite: 2]
* `Academic / Educational License` (Academic)[cite: 2]

---

## 📋 Pasos para la Activación Simula

1. **Ingreso de datos:** Introduce el **Nombre de Registro** (máximo 30 caracteres)[cite: 2]. El sistema limpiará de forma automática acentos y la letra `ñ` para preservar el formato estándar[cite: 2].
2. **Selección de licencia:** Selecciona un tipo de licencia de la parrilla inferior o introduce uno a medida en el campo correspondiente[cite: 2].
3. **Generación:** Haz clic en **⚡ Generar Licencia**[cite: 2]. Se iniciará una simulación de procesamiento asíncrono con estados de carga visuales[cite: 2].
4. **Copia / Descarga:** Utiliza el botón flotante **Copiar** o haz clic en **💾 Guardar rarreg.key** para exportar el archivo[cite: 2].
5. **Instalación:** Traslada el archivo resultante asegurándote de que se llame estrictamente `rarreg.key` al directorio raíz donde se encuentra instalado WinRAR en tu equipo[cite: 2].
6. **Validación:** Reinicia el software principal para auditar que reconozca los nuevos parámetros de registro de la prueba de concepto[cite: 2].

---

## 🛠️ Stack Tecnológico

- **HTML5 Semántico:** Estructuración limpia mediante el uso de etiquetas nativas y contenedores accesibles[cite: 2].
- **CSS3 Avanzado (Modern UI):** Implementación de Grid Layout para los bloques de licencias, Flexbox para alineaciones responsivas, animaciones keyframes (para spinners de carga) y Media Queries para una compatibilidad móvil perfecta (`max-width: 640px`)[cite: 2].
- **JavaScript (Vanilla JS - ES6+):** Arquitectura desacoplada basada en eventos, manipulación avanzada del DOM, lógica de codificación de caracteres, API de Portapapeles (`navigator.clipboard`) y persistencia mediante Web Storage[cite: 2].
- **Fuentes Tipográficas:** Carga optimizada de `Inter` para la interfaz de control y `JetBrains Mono` para la visualización del bloque de llaves de registro[cite: 2].

---

## ⚙️ Configuración y Uso Local

Al carecer de backend o servicios de terceros, no requiere entornos de Node.js, PHP ni servidores web locales de desarrollo. 

1. Clona el proyecto o descarga los archivos fuentes (`index-v3.html` y los scripts asociados `rarkeyok.js`)[cite: 2].
2. Asegúrate de estructurarlos en el mismo directorio.
3. Abre el archivo `index-v3.html` en cualquier navegador moderno (Chrome, Edge, Firefox, Safari)[cite: 2].

---

## ⚠ Requisitos Críticos de Compatibilidad

- **Sintaxis ASCII:** El nombre de usuario y tipo de licencia deben apegarse a caracteres estándar del alfabeto inglés. El script de la aplicación incluye un sanitizador integrado (`removeAccents`) para mitigar fallas de codificación[cite: 2].
- **Formato del Bloque:** No se debe alterar de forma manual el texto de salida generado dentro del campo de texto, ya que corromperá el formato esperado por el software durante la lectura en la simulación[cite: 2].
- **Nombre de Archivo:** El archivo guardado debe mantener con precisión minuciosa el nombre en minúsculas `rarreg.key`[cite: 2].

---

## 👥 Créditos

Desarrollado de forma interactiva con fines técnicos de demostración.

© 2018 – 2026 **ABTech**[cite: 2]
