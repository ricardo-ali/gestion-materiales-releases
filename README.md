# Gestion de Materiales - paquetes

Distribucion de la aplicacion portable para Windows x64. Este repositorio contiene paquetes compilados localmente y notas de version; no contiene codigo fuente, bases, Excel ni credenciales.

## Descargar

En [Releases](https://github.com/ricardo-ali/gestion-materiales-releases/releases), elegir el paquete completo `gestion-materiales-<version>-win-x64-*.zip`. Extraer y abrir `GestionMateriales.Host.exe`. Las instrucciones LEEME.md estan dentro del paquete.

Los ZIP `app-*`, `dotnet-*`, `duckdb-*` y `publisher-*`, junto con `app-update.json`, son componentes para el actualizador integrado; no se instalan manualmente.

Desde la version 0.9.0: Configurar > Actualizar App > Buscar Actualizacion. La aplicacion descarga los componentes necesarios y ofrece Reiniciar y actualizar. Conserva la configuracion personal en `%LOCALAPPDATA%\GestionMateriales\config.json` y no modifica las bases.

Las releases incluyen su estado de pruebas y limites. La disponibilidad publica de los binarios no asigna una licencia abierta al codigo del proyecto. Los avisos de terceros acompanian cada paquete.