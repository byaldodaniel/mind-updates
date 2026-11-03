# Mind — Windows x64

[**Descargar Mind 1.0.0 para Windows x64**](https://github.com/byaldodaniel/mind-updates/releases/download/v1.0.0/Mind-1.0.0-win32-x64.zip)

[Notas y archivos de la versión](https://github.com/byaldodaniel/mind-updates/releases/tag/v1.0.0)

1. Extrae el ZIP y conserva la carpeta `Mind` en una ubicación permanente.
2. Sigue `LEEME.md` para conectar Mind a tu agente una vez.
3. Abre tu carpeta de trabajo en el agente y pídele que use Mind.

Mind incluye sus runtimes. La carpeta abierta tiene acceso completo sin otro formulario cuando el cliente comunica la carpeta, inicia Mind desde ella o configura `--carpeta`. Borrar conserva su confirmación.

Desde esta versión, Mind comprueba las actualizaciones estables firmadas al iniciar y las instala cuando no hay sesiones activas. Sin conexión continúa con la versión instalada. Una copia anterior necesita recibir este paquete una vez mediante `mind actualizar`, con los agentes cerrados.

Esta publicación es exclusivamente para **Windows x64**. Linux y macOS quedan para entregas posteriores.

Validación de Windows: 354 pruebas aprobadas, 5 omitidas y cero fallos; 24/24 recorridos del paquete extraído y un ensayo completo de actualización automática con conservación de la Base. La conexión MCP con Claude Code se comprobó sin ejecutar un modelo.

Los archivos personales permanecen en su ubicación. La Base conserva metadatos y continuidad. Mind no proporciona aislamiento del sistema operativo. Consulta los límites y la licencia dentro del paquete.

Este repositorio contiene la distribución del producto. El historial y el trabajo de desarrollo se mantienen en un repositorio privado; el paquete incluye los archivos de programa necesarios para ejecutarlo.

Titular: Aldo Daniel.