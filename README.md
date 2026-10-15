# Gestión de Materiales - paquetes

Distribución de la aplicación portable para Windows 11 o posterior x64. Este repositorio contiene paquetes compilados localmente y notas de versión; no contiene código fuente, bases, Excel ni credenciales.

## Descargar

Enlace permanente: [Última release estable](https://github.com/ricardo-ali/gestion-materiales-releases/releases/latest). Siempre apunta a la versión estable marcada como Latest; no hace falta cambiarlo al publicar una nueva versión.

En esa página, elegir el paquete completo `gestion-materiales-<version>-win-x64-*.zip`. Extraer y abrir `GestionMateriales.Host.exe`. Las instrucciones LEEME.md están dentro del paquete.

Los ZIP `app-*`, `dotnet-*`, `duckdb-*` y `publisher-*`, junto con `app-update.json`, son componentes para el actualizador integrado; no se instalan manualmente.

## Actualizar desde la app

Las versiones 0.29.0 y posteriores consultan ese mismo canal estable mediante la API de GitHub. Usar **Configurar > Actualizar App > Buscar Actualizacion** y después **Reiniciar y actualizar**. No es necesario instalar versiones intermedias. Si no hay una release más reciente, la app conserva la versión instalada.

El actualizador está disponible desde la versión 0.9.0. Descarga los componentes necesarios, conserva la configuración personal en `%LOCALAPPDATA%\GestionMateriales\config.json` y no modifica las bases durante la actualización de la app.

Las releases incluyen su estado de pruebas y límites. La disponibilidad pública de los binarios no asigna una licencia abierta al código del proyecto. Los avisos de terceros acompañan cada paquete.
