# Descripción de la Arquitectura de Software
Este repositorio contiene la documentación de la arquitectura del sistema de Gestión hotelera del proyecto de la experiencia educativa de Diseño de Software de la Licenciatura en Ingeniaría de Software
## Objetivo

## Estructura del proyecto
- docs/ --> Documentaciön en AsciiDoc
- images/ --> Diagramas exportados desde EA
- build/ --> Salida generada (ignorada en Git)

## Requisitos
- Ruby (con Asciidoctor y Asciidoctor PDF instalados) .
- VS Code con el plugin [AsciiDoc by Asciidoctor] .
## Compilación local (bash)
- asciidoctor -D build docs/index.adoc
- asciidoctor-pdf -o build/index.pdf docs/index.adoc
