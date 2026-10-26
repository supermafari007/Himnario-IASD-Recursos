# Recursos multimedia del Himnario Adventista

Letras, música cantada, música instrumental y videos disponibles del Himnario. El catálogo principal contiene **613 himnos**; «Amenes» se conserva como complemento en los recursos 1.0.

Este repositorio distribuye únicamente los recursos. El código de las aplicaciones permanece privado.

## Letras renovadas · versión 2.0

**613 himnos y 4.871 láminas en 2048 × 1536 píxeles**, con mejoras de definición, contraste y símbolos temáticos.

| Descarga directa | Contenido | Tamaño aproximado |
| --- | --- | --- |
| [Letra-v2.0-Himnos-001-306.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v2.0/Letra-v2.0-Himnos-001-306.zip) | Himnos 1–306 | 1,48 GB |
| [Letra-v2.0-Himnos-307-613.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v2.0/Letra-v2.0-Himnos-307-613.zip) | Himnos 307–613 | 1,51 GB |

Descarga **ambos ZIP** y extrae su contenido en la misma carpeta de recursos. Los dos contienen `Letra/` y se complementan; no necesitan unirse con otro programa. La división respeta el límite por archivo de GitHub y conserva las imágenes sin reducir su calidad.

[Publicación de Letras 2.0, instrucciones y SHA-256](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/tag/v2.0).

Las letras 2.0 pueden descargarse manualmente o desde la edición oficial **Windows 2.1.8**, que descarga ambas partes como un solo componente y permite repararlo sin volver a descargar la música ni los videos.

## Descargas por componente · versión 1.0

| Componente | Descarga directa | Tamaño aproximado |
| --- | --- | --- |
| Letras originales | [Letra-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Letra-v1.0.zip) | 359 MB |
| Música cantada | [Cantado-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Cantado-v1.0.zip) | 1,95 GB |
| Música instrumental | [Instrumental-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Instrumental-v1.0.zip) | 1,55 GB |
| Videos cantados | [Video-Cantado-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Video-Cantado-v1.0.zip) | 344 MB |

[Publicación 1.0 y sumas SHA-256](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/tag/v1.0) · [Descargar el Himnario](https://github.com/supermafari007/Himnario-IASD-Actualizaciones#descargas)

Los ZIP de la versión 1.0 contienen los mismos archivos de los recursos anteriores, separados para facilitar descargas y reparaciones. Las letras recreadas se distribuyen aparte como versión 2.0.

## Uso desde el Himnario

La edición oficial **Windows 2.1.8** utiliza el [manifiesto estable de Windows](media-manifest-windows.json). Reconoce los contenidos instalados desde el ZIP completo anterior y permite elegir qué descargar o reparar. Al actualizar a Letras 2.0, se descargan sus dos partes y solo se sustituye ese componente cuando ambas se han comprobado e instalado por completo.

**Windows Legacy, macOS Intel/Apple Silicon y Linux continúan en 2.1.7** y conservan su canal y paquete multimedia actuales. Esta publicación no cambia sus actualizadores.

## Instalación manual

La biblioteca debe conservar esta estructura:

```text
Recursos Himnario/
  Letra/
  Musica/
    Cantado/
    Instrumental/
  Video Cantado/
```

Extrae las dos partes de Letras 2.0 —o el ZIP de letras originales 1.0— en la raíz de tu biblioteca. Extrae Video Cantado también en la raíz, y Cantado e Instrumental dentro de Musica. Windows Legacy utiliza letras y música, sin videos.

Para reparar un componente, conserva antes un respaldo si contiene archivos personalizados. Los componentes no seleccionados deben mantenerse intactos.

## Integridad y versiones

Cada ZIP tiene una suma SHA-256 en su publicación. El [manifiesto de componentes 1.0](media-manifest.json) conserva los recursos anteriores. El [manifiesto estable de Windows 2.1.8](media-manifest-windows.json) incorpora las letras 2.0 y mantiene la música y los videos en 1.0. El [manifiesto del Himnario Prueba](media-manifest-prueba.json) se conserva separado para desarrollo. El inventario adjunto a Letras 2.0 documenta las dos partes y las 4.871 láminas.

Los recursos se mantienen separados de los instaladores del programa. No se necesita iniciar sesión en GitHub para descargar estos archivos.
