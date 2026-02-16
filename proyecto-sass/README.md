👥 Integrantes del grupo

Integrante 1: Adrián Aránegas Molina

Integrante 2: David Sánchez Vázquez


proyecto-sass/
│
├─ scss/
│   ├─ base/
│   │   ├─ _reset.scss            
│   │   ├─ _tipografia.scss       
│   │   └─ _variables.scss       
│
│   ├─ layouts/
│   │   ├─ _header.scss          
│   │   |─ _footer.scss           
│   │              
│
│   ├─ components/
│   │   ├─ _buttons.scss          
│   │   ├─ _tipografias.scss      
│   │   └─ _forms.scss            
│
│   └─ main.scss                  
│
├─ html/                          
│   ├─ inicio.html
│   ├─ carta.html
│   ├─ contacto.html
│   └─ carrito.html
│
├─ img/                           
├─ css/main.css                     
└─ README.md


🔄Refactorizaciones respecto al CSS original

Extracción de variables para colores, fuentes y tamaños.

Uso de @extend para reutilizar reglas de .card-base.

Implementación de mixins para botones.

Uso de funciones de Sass: darken() , calc() .

Código más limpio y fácil de mantener.


✨ Ventajas que aporta SASS al proyecto

Reutilización: @extend y mixins evitan duplicar código.

Variables: facilitan cambios globales de color, fuente o tamaño.

Funciones y operadores: permiten cálculos automáticos (calc(), darken()).

Modularidad: los parciales SCSS permiten mantener el proyecto ordenado.

Mantenimiento sencillo: cambios en variables o mixins se aplican a toda la web.

Código más profesional y limpio: ideal para trabajar en equipo.