# Changelog
Todos los cambios notables a este proyecto serán docuemntados en este archivo.

El formato está basado en [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
y este proyecto adhiere a [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2019-12-26
### Added
- Se agrega soporte para Oneclick Mall y Transacción Completa en sus versiones REST.

## [1.1.0] - 2019-04-04
### Added
- Se agregaron los parámetros `qr_width_height` y `commerce_logo_url` a Options, para especificar el tamaño del QR generado para la transacción, y especificar la ubicación del logo de comercio para ser mostrado en la aplicación móvil de Onepay. Puedes configurar estos parámetros globalmente o por transacción.

## [1.0.1] - 2018-11-07
### Fixed
- En Onepay, se corrige error que impedía crear una transacción desde iOS.

### Security
- Actualización de dependencia a una versión libre de vulnerabilidades.

## [1.0.0] - 2018-10-23
### Added
- Primera versión del SDK de Transbank, que contiene solamente las funcionalidades para implementar Onepay.
