# L & G Óptica — Instaladores de Windows

Aplicación de escritorio para registrar pacientes, conservar graduaciones y dar seguimiento a sus consultas. Funciona sin conexión y sin inicio de sesión.

## Descargar

Los instaladores se encuentran en [Versiones](https://github.com/Bingo-Play/lg-client-manager-releases/releases). Elige la versión indicada por la óptica y descarga `LG-Optica-instalador-windows-x64.exe`. Los archivos `SHA256SUMS.txt` permiten comprobar la integridad de la descarga.

## Instalar

1. Usa Windows x64 y cierra la óptica si está abierta.
2. Ejecuta el instalador y sigue los pasos en español.
3. Abre **L & G Óptica** desde el menú Inicio.

La aplicación necesita WebView2. Si el equipo no lo tiene, la instalación de ese componente requiere Internet. Para instalar sin conexión, lleva previamente el instalador independiente **WebView2 Evergreen x64** desde [Microsoft](https://developer.microsoft.com/microsoft-edge/webview2/).

## Expedientes y actualizaciones

Los expedientes se guardan en `%APPDATA%\LG-Optica`, fuera de la carpeta de instalación. Las actualizaciones y la desinstalación conservan esa carpeta. Usa **Configuración → Crear respaldo** para guardar una copia en otra unidad.

El seguimiento se calcula entre 3 y 6 semanas desde la fecha de consulta. Los avisos se muestran al abrir la aplicación. La ficha de graduación se imprime en formato horizontal de **20 × 15 cm**, a escala del **100 %**, desde el visor PDF del equipo.

## Código y soporte

El código y la documentación técnica están en [Bingo-Play/lg-client-manager](https://github.com/Bingo-Play/lg-client-manager). Este repositorio contiene únicamente documentación de distribución y archivos adjuntos de versiones; no almacena expedientes ni datos de pacientes.

Los instaladores iniciales no incluyen firma Authenticode. La primera entrega debe revisarse con la impresora de la óptica antes de usarse con expedientes reales.
