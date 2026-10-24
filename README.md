# Recursos multimedia del Himnario Adventista

Letras, música cantada, música instrumental y videos disponibles del Himnario. El catálogo principal contiene **613 himnos**; «Amenes» se conserva como complemento.

Este repositorio distribuye únicamente los recursos. El código de las aplicaciones permanece privado.

## Descargas por componente · versión 1.0

| Componente | Descarga directa | Tamaño aproximado |
| --- | --- | --- |
| Letras | [Letra-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Letra-v1.0.zip) | 359 MB |
| Música cantada | [Cantado-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Cantado-v1.0.zip) | 1,95 GB |
| Música instrumental | [Instrumental-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Instrumental-v1.0.zip) | 1,55 GB |
| Videos cantados | [Video-Cantado-v1.0.zip](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/download/v1.0/Video-Cantado-v1.0.zip) | 344 MB |

[Publicación y sumas SHA-256](https://github.com/supermafari007/Himnario-IASD-Recursos/releases/tag/v1.0) · [Descargar el Himnario](https://github.com/supermafari007/Himnario-IASD-Actualizaciones#descargas)

Los ZIP contienen los mismos archivos de los recursos 1.0 anteriores, separados para facilitar descargas y reparaciones. No incluyen las láminas experimentales recreadas.

## Uso desde el Himnario

La integración por componentes se está probando en la copia local de **Windows 2.1.8**. Reconoce los contenidos instalados desde el ZIP completo anterior y permite elegir qué descargar o reparar, sin volver a descargar componentes que ya están disponibles.

Las ediciones oficiales **2.1.7** conservan su canal y paquete multimedia actuales. Esta publicación de recursos no cambia sus actualizadores.

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

Extrae Letra y Video Cantado en la raíz de tu biblioteca. Extrae Cantado e Instrumental dentro de Musica. Windows Legacy utiliza letras y música, sin videos.

Para reparar un componente, conserva antes un respaldo si contiene archivos personalizados. Los componentes no seleccionados deben mantenerse intactos.

## Integridad y versiones

Cada ZIP tiene una suma SHA-256 en la publicación. El [manifiesto de componentes](media-manifest.json) declara versiones independientes, enlaces, tamaños e inventarios. Una actualización de letras puede distribuirse sin cambiar ni descargar otra vez la música.

Los recursos se mantienen separados de los instaladores del programa. No se necesita iniciar sesión en GitHub para descargar estos archivos.
