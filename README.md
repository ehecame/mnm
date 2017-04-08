# Mapa ONU Mujeres

Un mapa que funciona como visualización interactiva de diez Métricas estadísticas de género en América Latina y el Caribe.

Dichas Métricas son navegables por País y Temas específicos.

Las Métricas podrán ser vistas para todos los países simultáneamente, o únicamente para uno.

La visualización de comparación entre países será realizada con una gráfica de barras. Al cargar los distintos años que comprenden una Métrica, se actualizará la gráfica, inclusive omitiendo en ocasiones países si para ellos no hay un valor para un año específico.

La visualización para un único país combinará una gráfica lineal (solo en los casos en que haya múltiples años) con una gráfica de barras o circular para el año siendo visualizado (por defecto, el más reciente).




### Interfaz General

- Cabecera
- Navegación Países
  - Mapa con siluetas de países
  - Lista Países
- Navegación Métricas
- Área Principal

### Vistas


#### Mapa

- Gama de colores para indicar magnitud.
- IxD:
- Al clicar un país, se cargará automáticamente la Vista **Métrica: País Individual**

#### Métrica: Multipaís

- Título
- Navegación
  - Navegación por Años (tabs)
- Gráfica Lineal (opcional)
- Gráfica Barras o Circular
- Fuente

#### Métrica: País Individual

  - Navegación
    - Botón regresar a "Todos los Países"
    - Dropdown de País
  - Gráfica Lineal
  - Gráfica Año Único
    - Gráfica Circular
    - Navegación por Años (tabs)



##### Componentes

- Gráfica Barras
  - Nombres de países
  - Gama de colores para indicar magnitud.
  - Aclaración de la Unidad de Métrica
  - Si la Métrica mide una Proporción, deberá mostrarse visualmente el 100%

- Gráfica Circular

- Gráfica Lineal


### Objetos de Contenido

- País
  - Nombre
- Tema
  - Nombre
- Métrica
  - Título
  - Fuente
  - Conjunto de Datos
    - Cada Dato
      - Año
      - Valor
  - Tipo de visualización
  - Unidad de medición (porcentaje, 1/100000, etc)


### Taxonomías

- Año
- País
