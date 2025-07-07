<div align="center">

F O R M A T O S - D I G I T A L E S
Una solución móvil para la digitalización y gestión de formatos de mantenimiento, eliminando el uso de papel y optimizando los flujos de trabajo.

</div>

<p align="center">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/React_Native-20232A%3Fstyle%3Dfor-the-badge%26logo%3Dreact%26logoColor%3D61DAFB" alt="React Native"/>
<img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/JavaScript-F7DF1E%3Fstyle%3Dfor-the-badge%26logo%3Djavascript%26logoColor%3Dblack" alt="JavaScript"/>
</p>

🚀 Descripción del Proyecto
Este proyecto nace de la necesidad de reducir el consumo de papel y modernizar el proceso de llenado de formatos de mantenimiento correctivo. La aplicación móvil permite a los técnicos buscar equipos, generar formatos dinámicamente, rellenarlos, capturar firmas digitales y compartir el documento final en PDF, todo desde su dispositivo móvil.

El sistema está diseñado para ser robusto, escalable y funcionar principalmente sin conexión a internet después de una sincronización inicial.

✨ Características Principales
📱 Interfaz Móvil Intuitiva: Diseño limpio y moderno centrado en la facilidad de uso para el personal técnico.

🔄 Sincronización Offline: La app descarga y almacena localmente la base de datos de equipos y todas las plantillas de formatos PDF, permitiendo un funcionamiento completo sin conexión a internet.

🔍 Búsqueda Inteligente: Búsqueda rápida de equipos por su número de inventario.

📄 Generación Dinámica de Formularios: La aplicación analiza cualquier plantilla PDF y genera automáticamente un formulario nativo con sus campos correspondientes (texto, checkboxes, etc.), eliminando la necesidad de programar formularios manualmente.

✍️ Edición y Firma Digital: Permite rellenar los campos y capturar firmas manuscritas directamente en la pantalla, que luego se incrustan en los campos de firma del PDF original.

📤 Guardado y Uso Compartido: Genera un nuevo PDF finalizado y abre el menú nativo del sistema para compartirlo instantáneamente por correo, WhatsApp, etc.

🛠️ Tecnologías Utilizadas
Framework: React Native con Expo

Lenguaje: JavaScript (ES6+)

Manejo de PDF: pdf-lib para la manipulación y react-native-pdf para la visualización.

Firma Digital: react-native-signature-canvas

Sistema de Archivos: expo-file-system para la gestión de datos offline.

Componentes Nativos: expo-checkbox, expo-sharing.

⚙️ Flujo de Trabajo
Actualizar: El técnico presiona un botón para descargar la base de datos de equipos y todas las plantillas de formatos desde un repositorio central (GitHub).

Buscar: Ingresa el número de inventario de un equipo.

Visualizar: La app muestra los detalles del equipo encontrado.

Llenar: Se abre el editor, que muestra el formato PDF y superpone campos nativos para una fácil edición.

Firmar: El técnico y/o supervisor firman en un lienzo digital.

Guardar y Compartir: La app genera el PDF final con todos los datos y firmas incrustadas y lo deja listo para ser compartido.

<p align="center">
Desarrollado con ❤️ para un futuro más eficiente y sin papel.
</p>
