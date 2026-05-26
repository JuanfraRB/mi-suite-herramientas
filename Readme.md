# 🛠️ Suite de Herramientas de Gestión Local

¡Bienvenido a la **Suite de Herramientas de Gestión**! Este proyecto es una colección de 8 aplicaciones web estáticas, optimizadas y ligeras, diseñadas para resolver tareas cotidianas de cálculo, edición y organización de personal sin depender de bases de datos externas.

Todo el ecosistema funciona de manera **local y segura** en el navegador a través de la API `localStorage`, garantizando una velocidad instantánea y total privacidad de los datos.

---

## 🚀 Características Principales

* **Diseño Unificado:** Todas las herramientas comparten una hoja de estilos global (`/css/estilos.css`) diseño responsivo y modo limpio.

* **Zero Backend:** Aplicación 100% *Serverless* e indexable, ideal para ser desplegada en plataformas como **Vercel**, **GitHub Pages** o **Netlify**.

* **Persistencia Local:** Tus datos no viajan a ningún servidor; se guardan automáticamente en tu navegador.

* **Exportación Avanzada:** Motores integrados para guardar tus resultados en archivos nativos HTML, imágenes o documentos **PDF**.

---

## 📱 Aplicaciones Incluidas

El proyecto está dividido en módulos independientes y accesibles:

1. **Calculadora de Jornada y Horas Anuales (`calculo_horas.html`):** Control de balances de horas mensuales con cómputo anual, control de vacaciones y cobro de horas extras.
2. **Control de Vacaciones de Personal (`calculo_vacaciones.html`):** Planificador cromático interactivo para hasta 10 personas con límite de periodos de 15 días y exportación optimizada a PDF apaisado.
3. **Editor Markdown(`editor_markdown.html`):** Entorno de desarrollo con barra de comandos rápida, inserción inteligente de sintaxis por posición de cursor, scroll síncrono y panel de ayuda colapsable.
4. **Conversor de imágenes(`conversor_imagenes.html`):** Compresor y convertidor de imágenes.
5. **Divisor PDF (`divisor.html`):** divide un archivo pdf en páginas y cada página se guarda en una archivo, se puede seleccionar el número de páginas a dividir, descargando un paquete..
6. **Control de Finanzas personal(`finanzas.html`):** Control de ingresos y gastos para control de finanzas personal básico.
7. **Tablero Kanban(`tablero_kanban.html`):** tablero básico para control de tareas pendientes, realizando y finalizadas.
8. **Generador y lector de QR(`pr_tool.html`):** Genera código QR de un texto o URL o leer un archivo imágen de un qr para saber su contenido.

---

## 🛠️ Estructura del Proyecto

```text
├── css/
│   └── estilos.css       # Hoja de estilos (Colores, Reset, Cards, Botones)
├── calculo_horas.html     # Calculadora de balances de jornada anual
├── calculo_vacaciones.html# Cuadrante organizador de vacaciones + Exportación PDF
├── conversor_imagenes.html # Compresor, conversor de imágenes
├── divisor.html            # Divide un PDF en varios archivos
├── editor_markdown.html   # Editor con panel de ayuda dinámico y renderizado en vivo
├── finanzas.html         # Control financiero personal
├── index.html            # menú inicial
├── qr_tool.html          # Lector, generador QR
├── vercel.json           # Configuración de enrutamiento y optimización para Vercel
└── README.md             # Documentación general del proyecto (Este archivo)
