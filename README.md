# APE 3 · Integración y Pruebas — Gestión Jerárquica con Árboles

**Universidad Técnica de Ambato**  
**Facultad de Ingeniería en Sistemas, Electrónica e Industrial**  
**Carrera de Software · Estructura de Datos (Tercero "B")**  

---

##  Datos Informativos
* **Proyecto:** APE 3 · Fase de Integración y Pruebas
* **Grupo:** Grupo 4
* **Asignatura:** Estructura de Datos
* **Docente:** Ing. José Caiza, Mg.

---

##  Integrantes del Equipo
* Lenin Maigua
* Josué Caguana
* Kleber Andrés Moyota
* Cris Yanchatipan
* Héctor Villacís

---

## Descripción del Proyecto
Este repositorio corresponde a la **APE 3**, enfocada en la **integración, modelado y pruebas de estructuras de datos jerárquicas (Árboles)** en Java. El sistema implementa la gestión organizacional y de estudiantes a través de nodos enlazados, permitiendo inserciones, búsquedas y recorridos especializados (Preorden, Inorden y Posorden) aplicados a unidades académicas y expedientes estudiantiles.

---

##  Arquitectura y Estructura de Paquetes
El código fuente se encuentra organizado de forma modular bajo el directorio `src/`:

```text
src/
├── app/
│   ├── Contexto.java
│   └── Main.java
├── enums/
│   ├── TipoRecorrido.java
│   └── TipoUnidad.java
├── modelo/
│   ├── Estudiante.java
│   └── UnidadAcademica.java
├── negocio/
│   ├── ArbolEstudiantes.java
│   ├── ArbolOrganizacional.java
│   ├── NodoEstudiante.java
│   └── NodoUnidad.java
└── pruebas/
    ├── PruebasJosue.java
    └── PruebasLenin.java
