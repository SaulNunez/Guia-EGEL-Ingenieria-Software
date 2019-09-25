
# EGEL INGENIERIA DE SOFTWARE

## Análisis de sistemas de información
### Diagnóstico del problema y valoración de la factibilidad para el desarrollo de sistemas de información

#### Análisis preliminar de los sistemas de operación de la organización 
#### Diagnóstico de la situación de los sistemas de operación de la organización
#### Identificación de los problemas a resolver con sistemas de información 
#### Análisis de factibilidad de productos comerciales contra desarrollos a la medida como estrategias de solución del problema 
#### Propuestas de sistemas de información computacional que solucionen la problemática detectada en la organización 

### Modelado de los requerimientos de un sistema de información 
#### Análisis de los requerimientos de un sistema de información 
#### Validación de los requerimientos de un sistema de información 
#### Documentación de los requerimientos de un sistema de información

## Desarrollo e implantación de aplicaciones computacionales
### Diseño de la solución del problema de tecnología de información 
#### Análisis de los requerimientos de un sistema de información 
#### Validación de los requerimientos de un sistema de información 
#### Documentación de los requerimientos de un sistema de información
### Desarrollo de sistemas
#### Herramientas de desarrollo del sistema 
#### Codificación del sistema 
#### Validación de la solución tecnológica 
#### Ajuste del producto de software desarrollado

### Implantación de sistemas 
#### Técnicas de implantación de sistemas 
#### Elementos para poner en operación un producto de software 
#### Pruebas de operación y validez de un producto de software 

### Aplicación de modelos matemáticos
#### Aplicación de las ciencias básicas a la ingeniería de software 
#### Simulación de sistemas mediante herramientas computacionales 

## Gestión de proyectos de tecnologías de información
### Administración de proyectos de tecnologías de información
#### Administración de  los recursos de proyectos de tecnologías de información 
#### Verificación del cumplimiento de las metas del proyecto de tecnologías de información 

### Control de calidad de proyectos de tecnologías de información 
#### Selección de los modelos de calidad para tecnologías de información 
#### Aplicación de metodologías para el modelo de calidad seleccionado 
#### Establecimiento de las métricas de calidad para proyectos de tecnologías de información 
#### Verificación del cumplimiento de las métricas de calidad en proyectos de tecnologías de información 

## Implementación de redes, bases de datos, sistemas operativos y lenguaje de desarrollo
### Gestión de redes de datos 
#### Diseño de modelos de redes en base a un requerimiento de una organización 
#### Implementación redes de datos 
#### Administración y operación de una red de datos 

### Gestión de bases de datos
#### Diseño de bases de datos relacionales 
##### Formas normales
La normalización nos permite organizar los datos de una base de datos, incluye la creación de tablas y el establecimiento de relaciones según reglas con el fin de que la base de datos sea mas flexible al eliminar redundancia y dependencias incoherentes, las dependencias incoherentes evitan que el acceder a los datos sea intuitivo y dificulta el acceso por que la ruta puede no estar o estar interrumpida.
###### Primera forma normal
* Eliminar grupos repetidos de información de las tablas individuales. Eliminar cosas como `proveedor_1` y `proveedor_2`, mudarlo a una tabla de proveedores; eliminar campos como información del usuario si lo principal son las ordenes de compra.
* Crear tablas independientes para cada conjunto de datos relacionados.
* Identificar cada tabla con un llave primaria.

##### Segunda forma normal
* Crear tablas independientes para conjuntos de valores que se apliquen a varios registros. Por ejemplo, si tienes dirección en la tabla de clientes y de facturas independientemente en ambas tablas, considera tenerlo solo en una tabla.
* Relacionar estas tablas con una clave externa.

##### Tercera forma normal
* Eliminar campos que no dependan de la clave.

#### Implementación de bases de datos
#### Administración, instalación, configuración y mantenimiento de una base de datos 

### Gestión de sistemas operativos o lenguajes de desarrollo
#### Selección del sistema operativo o lenguaje de desarrollo de acuerdo a las características y necesidades de la organización 
#### Configuración de sistemas operativos   
#### Administración de servidores 