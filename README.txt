DIRECTORA VIRTUAL MK - VERSIÓN 2

INSTALACIÓN GITHUB PAGES
1. Extraer el ZIP.
2. Subir TODOS los archivos directamente a la raíz de un repositorio en GitHub.
3. Settings > Pages > Deploy from branch > main > / (root).
4. Abrir el sitio HTTPS y en el navegador instalar la PWA si lo permite.

NOVEDADES V2
- Nueva pestaña «Importar y consultar».
- Importación de CSV, XLS/XLSX y PDF con texto extraíble.
- Vista previa antes de guardar, selección de filas, detección de duplicados.
- Actualizar consultoras existentes por código o agregar solo nuevas.
- Preservar los valores previos en celdas vacías de producción (por defecto).
- Consultar por código/nombre de consultora o código/nombre de iniciadora.
- Reportes de grupo con producción SEP-AGO, totales e impresión.
- Conserva todos los módulos de V1 y sus datos locales.

CUIDADOS ESENCIALES
- Esta es una importación ASISTIDA, no una conversión fiel universal de PDF. Los formatos de reportes varían: revisar minuciosamente la vista previa contra el PDF original, con especial cuidado en iniciadoras, meses e importes. El PDF de escaneo SIN texto no es compatible: aplicar OCR antes de subir. Los reportes con subtotales intercalados pueden requerir adaptar el formato.
- Excel y PDF requieren descargar sus motores de lectura desde cdnjs.cloudflare.com durante su uso (necesitan conectividad); no vienen incluidos dentro del ZIP. CSV funciona sin esas librerías.
- Antes de importar, descargar respaldo JSON. Si existían registros se actualizarán por código y su producción detectada. Los meses vacíos se conservan por defecto.
- Si hace falta, recargar la aplicación después de importar para actualizar todos los paneles de V1.
- NO existe sincronización ni servidor: los datos se guardan exclusivamente en localStorage en el navegador de cada dispositivo; NO están cifrados y no están protegidos por contraseña. No usar en equipos compartidos para datos personales sensibles.
- Al reemplazar la V1 en GitHub Pages manteniendo el mismo sitio/dominio/ruta, los datos de localStorage se conservan normalmente. Respaldar antes.
- Aplicación independiente, NO oficial de Mary Kay Inc. No envía WhatsApp ni conecta sistemas oficiales.
