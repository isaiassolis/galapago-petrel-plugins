![Galápago Performance Suite](docs/assets/galapago-banner.svg)

# Galápago Performance Suite
### Caso de estudio profesional · Extensiones para Petrel

**Diseño, dirección de desarrollo y programación de dos productos de software especializado para la gestión de información técnica en proyectos de administración de yacimientos.**

**Productos:** [Galápago Clear](docs/GALAPAGO-CLEAR.md) · [Galápago Save](docs/GALAPAGO-SAVE.md)  
**Entorno de integración:** Petrel (Schlumberger)  
**Tecnologías de implementación confirmadas por el autor:** C#, .NET y Ocean SDK  
**Formación relacionada:** capacitación/certificación Ocean de Schlumberger, declarada por el autor; modalidad y credencial exactas pendientes de comprobar.

> **Tipo de repositorio:** caso de estudio histórico y documentación funcional. **No contiene código fuente, instaladores, SDK, datos petroleros ni componentes propietarios** de Petrel, Ocean o los productos Galápago. La información se basa en una presentación histórica de 18 páginas y en la descripción de la participación profesional proporcionada por el autor.

## Contexto y problema

**Galápago Performance Suite** se presentó como una línea de herramientas de Plenumsoft para complementar la plataforma Petrel mediante plugins que integran algoritmos o automatizan procesos.

La documentación histórica identifica dos necesidades:

- **Depuración y exploración de información técnica:** proyectos con elementos repetidos y tiempos elevados de identificación y limpieza de información.
- **Resguardo y documentación de proyectos:** riesgo de pérdida de información, documentación dispersa y dificultad para localizar variables técnicas.

## Productos desarrollados

| Producto | Problema abordado | Capacidades documentadas |
| --- | --- | --- |
| **[Galápago Clear](docs/GALAPAGO-CLEAR.md)** | Información repetida y depuración laboriosa en proyectos Petrel. | Identificación de variables repetidas; consulta de pozos, cimas, cubos sísmicos, fallas y horizontes; comparación de registros geofísicos de dos pozos. |
| **[Galápago Save](docs/GALAPAGO-SAVE.md)** | Resguardo y organización de información técnica de proyectos. | Automatización del proceso de resguardo; fichas técnicas y reportes; documentación complementaria; georreferenciación; exportación documental. |

### Galápago Clear

El plugin permitía consultar información del proyecto sin recorrer manualmente las carpetas del panel *Input*, identificar ciertos elementos repetidos y comparar registros geofísicos de dos pozos desde una ventana propia.

[Leer el caso de estudio de Clear →](docs/GALAPAGO-CLEAR.md)

### Galápago Save

El plugin orientaba el resguardo de proyectos de administración de yacimientos, incluyendo documentación técnica, fichas, reportes y archivos complementarios, además de datos de georreferenciación.

[Leer el caso de estudio de Save →](docs/GALAPAGO-SAVE.md)

## Mi participación

**Rol declarado por el autor: diseño, dirección y programación de ambos productos.**

- Diseño funcional de herramientas orientadas a necesidades de trabajo en Petrel.
- Dirección del desarrollo de Galápago Clear y Galápago Save.
- Programación de los plugins en **C# y .NET**, utilizando **Ocean SDK** para su integración con Petrel.
- Formación especializada en Ocean de Schlumberger para el trabajo de integración.

**Pendiente de documentar:** versiones de .NET, C# y Ocean SDK; alcance del equipo dirigido; fechas exactas; denominación oficial de la credencial Ocean; y resultados medidos. No se atribuyen versiones, certificaciones específicas o métricas sin confirmación.

## Tecnologías utilizadas

- **C#:** lenguaje de programación de los dos plugins.
- **.NET:** plataforma de desarrollo utilizada.
- **Ocean SDK:** kit de desarrollo empleado para integrar las extensiones con Petrel.
- **Petrel:** plataforma anfitriona de las herramientas.

Esta pila tecnológica fue confirmada por el autor; la presentación histórica describe las funciones, pero no detalla versiones ni arquitectura interna.

## Enfoque técnico

```text
Usuarios de Petrel
       |
       v
Plataforma Petrel
       |
       +-- Galápago Clear
       |     +-- Consulta y detección de elementos repetidos
       |     +-- Exploración de variables del proyecto
       |     +-- Comparación de registros de pozo
       |
       +-- Galápago Save
             +-- Proceso de resguardo
             +-- Ficha técnica y reportes
             +-- Documentos complementarios
             +-- Georreferenciación
```

*Esquema funcional elaborado a partir de la presentación histórica. No representa la arquitectura interna ni las APIs específicas de implementación.*

## Evidencia documental

La presentación **«Presentación Galápago · julio de 2018»** describe los problemas, funcionalidades y ventajas de ambos productos. Las secciones relevantes son:

- **Páginas 3–10:** línea Galápago Performance Suite y Galápago Clear.
- **Páginas 11–18:** Galápago Save.

Las capturas originales aparecen en dicha presentación. **No se redistribuye aquí el PDF ni sus imágenes** hasta confirmar los derechos de publicación de los materiales corporativos. Ver [fuentes, límites y pendientes](docs/FUENTES-Y-ALCANCE.md).

## Propiedad intelectual y alcance

Este repositorio es una **descripción de experiencia profesional**, no un proyecto open source ni una distribución de productos de Plenumsoft o Schlumberger. Los nombres de productos y marcas pertenecen a sus respectivos titulares. No se declara afiliación actual ni autorización de distribución.

No se han verificado compilaciones, rendimiento, fechas de despliegue, licencias, ni detalles internos de implementación. La documentación distingue las capacidades descritas históricamente de los resultados medidos, que no están disponibles.

---

[← Portafolio profesional](https://github.com/isaiassolis)
