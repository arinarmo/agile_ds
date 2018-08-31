# _Agile_ Data Science

## Metodologías _Agile_

_Agile_ es un conjunto de **metodos y metodologías** diseñados para lidiar con  ciertos problemas comunes en el
desarrollo de _software_. Son relativamente sencillos de entender y de implementar.

Estas metodologías abarcan todas las áreas del desarrollo de _software_, incluyendo _project management_, 
_software design_ y _process improvement_. Cada uno de estos métodos consiste de **prácticas** que están diseñadas 
para su fácil adopción.

_Agile_ también es un _mindset_, enfocado en la colaboración y la comunicación. Idealmente, el equipo completo 
participa en la planeación y la toma de decisiones del proyecto, en lugar de que lo dicte un jefe o _project manager_. 
Para lograr que todo el equipo adopte un _mindset_ efectivo, cada metodología ágil cuenta con un conjunto de 
**valores** que sirven como guía.

Aunque algunas prácticas ágiles pueden dar resultado por si mismas, es necesaria la adopción del _mindset_ correcto para que su eficacia sea lo mayor posible.

### ¿Por qué _Agile_?

* Es más fácil lograr cumplir los objetivos antes de la fecha límite
* Surgen muchos menos _bugs_ en el código o proyecto
* El código o proyecto se vuelve más fácil de mantener
* Los usuarios suelen estar más conformes con el desarrollo del proyecto
* Por todo lo anterior, los miembros del equipo logran un mejor balance vida/trabajo, lo que los hace aún más efectivo

### Ejemplo: _Daily Standup_

Una práctica fácil de adoptar es el _standup_ diario, en el cual los miembros del equipo hablan acerca del trabajo que 
están realizando y los retos y bloqueos que se encuentran en este proceso. Esta "junta" debe de ser corta y concisa, por 
lo que los miembros del equipo deben mantenerse de pie durante la duración de la misma.

Durante un _standup_ diario:
* Se da la comunicación entre miembros del equipo
* La colaboración sucede cuando se describe un problema que otro miembro puede ayudar a resolver
* El o los líderes del proyecto se mantienen al tanto del estatus del proyect

Aunque es una práctica sencilla, que da resultados en si misma, el _standup_ diario es particularmente efectivo cuando
todos los miembros del equipo se mantienen atentos durante toda la junta, y tienen la actitud correcta hacia ella. Si 
algunos miembros del equipo sienten que están siendo obligados a estar en una junta innecesaria, en lugar de ver el
beneficio que les trae explicar su trabajo y escuchar el de los demás, la  efectividad de esta práctica disminuye. 
Del mismo modo, si el líder del proyecto lo  toma como una oportunidad para exigir o reprender, o si se ve como un
mecanismo de reporte ante el jefe, la práctica no logra su cometido deseado.

### Valores

* **Individuos e interacciones** sobre procesos y herramientas
* **_Software_ funcional** sobre documentación comprehensiva
* **Colaboración con el cliente** sobre negociación de contrato
* **Responder al cambio** sobre seguir un plan

## Algunas Metodologías _Agile_

### Scrum

Es la metodología más comúnmente adoptada. En _Scrum_ el proyecto se divide en _sprints_, 
ciclos de igual longitud (típicamente dos semanas o 30 días) que siguen las siguientes reglas:

Al inicio del _sprint_, ocurre la planeación, donde se decidirá que _features_ se
desarrollarán durante ese _sprint_. Esto forma el _backlog_ del _sprint_. Cada día, se tiene
un _standup_ diario, llamado _scrum_. Al final del _sprint_, se muestra el avance logrado y 
se tiene una junta de retrospección, en la cual se busca qué podemos aprender de ese _sprint_.

Hay dos roles cruciales en esta metodología, el líder o dueño del proyecto, que determina
el _backlog_ del producto (del cual se alimentan el _backlog_ del _sprint_, y el 
_scrum master_, quien organiza el _standup_ diario y guía el equipo en la metodología.
Estos roles pueden ser fijos o pasar periódicamente a diferentes miembros del equipo.


### Tablero Kanban

Desarrollado en los 40s por Toyota para manufactura e ingeniería. Es una manera visual de mostrar que partes se 
necesitan y cuál es el estatus de cada una. En la actualidad se utiliza para llevar el control de tareas en 
metodologías ágiles. Consiste en un tablero (físico o digital) dividido en columnas, en las cuales se colocan
tarjetas, cada una representando una tarea, y se asignan a la columna correspondiente según su estatus. Podemos
usar colores para representar algún detalle importante de la tarea: tipo de tarea, urgencia, etc.

Cada equipo puede diseñar su tablero según considere conveniente, pero es importante mantener algunas reglas básicas:

* Las tareas se mueven de izquierda a derecha conforme se realizan
* La primera columna debe representar el _backlog_ de tareas. Aquí se agregan tareas nuevas
* La última columan representa tareas terminadas.

A menudo, un Tablero Kanban se combina con alguna otra metodología ágil para lograr tanto una planeación efectiva como
una organización visual del avance del proyecto.

### Otras

**XP**: eXtreme Programming, es una metodología basada en aceptar el cambio y desarrollar 
features sólo cuando sea necesario, no cuando se cree que lo será. El trabajo se organiza en 
*quarters*, con subciclos semanales. En la planeación se agrega cierta **holgura** con 
features o tareas opcionales que pueden abandonarse si el equipo se atrasa.

**FDD**: Feature-Driven Development, se enfoca en convertir **modelos** en _software_ 
siguiendo iteraciones quincenales. Cada modelo consiste en una lista de features a implementar
 A diferencia de otras metodologías, hay una serie de pasos estrictos para producir
  _software_ viable consistentemente. Especificación de dominio, diseño, 
  desarrollo e inspección

**Crystal**: Una metodología más ligera, organiza el trabajo según qué tan crítico es cada
_feature_ o tarea. Típicamente hay 4 niveles: _Comfort_, _Discretionary Money_, _Money_ y _Life_.

 
## _Agile_ en la Ciencia de Datos

En la Ciencia de Datos, como en el desarrollo de _software_, equipos colaboran para entregar valor a través de
procesos complejos: diseño, análisis, programación, etc. Las metodologías ágiles proveen una manera de organizar
este trabajo y asegurar que entreguemos valor de una manera consistente y temprana.

Algunos aspectos de la metodología ágil aplican especialmente a la Ciencia de Datos:

### La importancia de iterar

Dificilmente se logra tener un análisis certero o un producto de Ciencia de Datos terminado "a la primera". A menudo
se requiere iterar. Si logramos entregar valor en cada ciclo de desarrollo, naturalmente iteramos de una manera
eficiente

### Entregar salidas intermedias

Como en el desarrollo de _software_, un problema frecuente en la Ciencia de Datos es que el análisis realizado o
los modelos predictivos construidos pueden no ser lo que se esperaba por el cliente. Mientras más tiempo pase entre
la especificación y la entrega, es más probable que surjan malentendidos y sea difícil ajustar requerimientos. Planear
entregables "pequeños" nos ayuda a validar la ruta que estamos tomando, y adaptarnos al cambio en los requerimientos
o a la llegada de nueva información

### ¿Experimentos o tareas?

A diferencia de la ingeniería o el desarrollo de _software_, la **ciencia** de datos se basa en experimentos. Un
resultado negativo es un resultado valioso y debe ser tomado como tal. Es importante que al organizar el trabajo y 
definir metas para un ciclo de desarrollo se tenga claro qué consiste en un experimento y qué en una tarea. Intentar
encontrar un modelo predictivo para algún fenómeno de interés dados ciertos datos puede verse como un experimento,
mientras que preparar este modelo para su uso en un sistema es más claramente una tarea.

******


## Primera herramienta: Git

## Git para Ciencia de Datos

## Segunda herramienta: Kanban

## Kanban para Ciencia de Datos

## Combinando Git y Kanban

## Referencias