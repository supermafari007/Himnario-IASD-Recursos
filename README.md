# Recursos multimedia del Himnario Adventista

Letras, música cantada, música instrumental y videos disponibles del Himnario. El catálogo principal contiene **613 himnos**; «Amenes» se conserva como complemento en los recursos 1.0.

Este repositorio distribuye únicamente los recursos. El código de las aplicaciones permanece privado.

## Himnos adicionales · versión 1.0

Ocho himnos nacionales —Argentina, Bolivia, Chile, Colombia, Ecuador, Paraguay, Perú y Uruguay— y los himnos de Aventureros, Conquistadores y Guías Mayores. Incluye **50 láminas panorámicas en 3840 × 2160, 11 pistas MP3 e iconos**, para Solo letra y Cantado con avance sincronizado.

[Descargar Himnos adicionales 1.0 e instrucciones](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/tag/adicionales-v1.0) · **403 MB**

La integración automática está disponible en **Himnario Prueba para Windows 2.2.0**. Cuando el paquete falta, se ofrece como nueva descarga opcional; también se puede reparar por separado. Los 613 himnos y la música ya instalada se conservan. La aplicación 2.2.0 continúa en pruebas locales y no se publica aquí una actualización oficial del programa.

La instalación manual coloca `Himnos Adicionales/` junto a `Letra/` y `Musica/`. Su [manifiesto propio de la prueba 2.2.0](media-manifest-2.2.json) conserva los canales que utilizan las aplicaciones anteriores.

## Letras renovadas · versión 2.0

**613 himnos y 4.871 láminas en 2048 × 1536 píxeles**, con mejoras de definición, contraste y símbolos temáticos.

| Descarga directa | Contenido | Tamaño aproximado |
| --- | --- | --- |
| [Letra-v2.0-Himnos-001-306.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v2.0/Letra-v2.0-Himnos-001-306.zip) | Himnos 1–306 | 1,48 GB |
| [Letra-v2.0-Himnos-307-613.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v2.0/Letra-v2.0-Himnos-307-613.zip) | Himnos 307–613 | 1,51 GB |

Descarga **ambos ZIP** y extrae su contenido en la misma carpeta de recursos. Los dos contienen `Letra/` y se complementan; no necesitan unirse con otro programa. La división respeta el límite por archivo de GitHub y conserva las imágenes sin reducir su calidad.

[Publicación de Letras 2.0, instrucciones y SHA-256](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/tag/v2.0).

Las letras 2.0 pueden descargarse manualmente o desde las ediciones oficiales **Windows, Windows Legacy, macOS y Linux desde 2.1.8**, que descargan ambas partes como un solo componente y permiten repararlo sin volver a descargar la música ni los videos.

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

Windows desde 2.1.8 utiliza el [manifiesto estable de Windows](media-manifest-windows.json); macOS Intel y Apple Silicon desde 2.1.8 utilizan el [manifiesto estable de macOS](media-manifest-macos.json). Todas estas ediciones reconocen los contenidos instalados desde el ZIP completo anterior y permiten elegir qué descargar o reparar. Al actualizar a Letras 2.0, se descargan sus dos partes y solo se sustituye ese componente cuando ambas se han comprobado e instalado por completo.

**Linux desde 2.1.8** utiliza [media-manifest-linux.json](media-manifest-linux.json) con cuatro componentes. **Windows Legacy desde 2.1.8** utiliza [media-manifest-windows-legacy.json](media-manifest-windows-legacy.json) con Letras, Cantado e Instrumental, sin video. Ambos reconocen la biblioteca anterior y ofrecen actualizar Letras a 2.0. Los canales antiguos se conservan para las versiones anteriores.

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

Cada ZIP tiene una suma SHA-256 en su publicación. El [manifiesto de componentes 1.0](media-manifest.json) conserva los recursos anteriores. Los manifiestos estables de [Windows 2.1.8](media-manifest-windows.json) y [macOS 2.1.8](media-manifest-macos.json) incorporan las letras 2.0 y mantienen la música y los videos en 1.0. El [manifiesto del Himnario Prueba](media-manifest-prueba.json) se conserva separado para desarrollo. El inventario adjunto a Letras 2.0 documenta las dos partes y las 4.871 láminas.

Los recursos se mantienen separados de los instaladores del programa. No se necesita iniciar sesión en GitHub para descargar estos archivos.
