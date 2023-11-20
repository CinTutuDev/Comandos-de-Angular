<p align="center"> 
 <img src="assets/angular.png" width="6%">
</p>
<p align="center"> 
<img src="https://readme-typing-svg.demolab.com?font=Pixel Emulator&size=40&color=DD0031&center=true&vCenter=true&width=940&lines=Comandos+De+Angular" align="middle" alt=""  width="80%"/>
</p>

# ${\color{orange}📚Indice }$

 1. ##  ${\color{#04d220}Iniciar\space el \space Proyecto}$<a href="#iniciar-el-proyecto"> 🖲</a>
   - ${\color{#04d220}Instalar\space  Angular\space Material}$<a href="#instalar-angular-material"> 🖲</a>

   - ${\color{#04d220}Cambiar\space directorio\space del\space proyecto\space}$<a href="#instalar-angular-material"> 🖲</a>

2. ##  ${\color{#04d220}Iniciar\space en\space servidor}$<a href="#iniciar-en-servidor">🌐</a>

3. ##  ${\color{#04d220}Cambiar\space puertos}$<a href="#cambiar-puertos">⚙️</a>
4. ##  ${\color{#04d220}Componentes}$<a href="#componentes">🔧</a>
  -  ${\color{#04d220}Crear\space  nuevo\space componente}$<a href="#crear-nuevo-componente">🔧</a>
      * ${\color{#04d220}Sin\space tests}$<a href="#sin-tests">🔧</a>
      *  ${\color{#04d220}Sin\space tests\space y \space hoja\space de\space estilos}$<a href="#sin-tests-y-estilos">🔧</a>
      * ${\color{#04d220}Sin\space template}$<a  href="#sin-template">🔧</a>
      * ${\color{#04d220}En\space otro \space directorio}$<a href="#en-otro-directorio">🔧</a>
      * ${\color{#04d220}Generar\space componente \space dentro\space del\space app-module}$<a href="#generar-componente-dentro-del-app-module">🔧</a>
      * ${\color{#04d220}Generar\space componente \space dentro\space de\space otro\space componente}$<a href="#generar-componente-dentro-de-otro-componente">🔧</a>
      *  ${\color{#04d220}Sin\space importar \space en\space app-module}$<a href="#sin-importar-en-app-module">🔧</a>
      
5. ##  ${\color{#04d220}Modulos}$<a href="#modulos">🧩</a>
  -  ${\color{#04d220}Crear\space nuevo\space modulo}$<a href="#crear-nuevo-modulo">🧩</a>
   
   -  ${\color{#04d220}Especificar\space carpeta\space de\space destino}$<a href="#especificar-carpeta-de-destino">🧩</a>

   -  ${\color{#04d220}Crear\space modulo\space con\space enrutamiento}$<a href="#crear-modulo-con-enrutamiento">🧩</a>

   -  ${\color{#04d220}Crear\space componente\space en\space el\space modulo}$<a href="#crear-componente-en-el-modulo">🧩</a>

6.  ##  ${\color{#04d220}Servicios}$<a href="#servicios">📡</a>
 - ${\color{#04d220}Crear\space nuevo\space servicio}$<a href="#crear-nuevo-servicio">📡</a>

7.  ##  ${\color{#04d220}Routing}$<a href="#routing">📡</a>
 - ${\color{#04d220}Configurar\space Enrutamiento\space}$<a href="#configurar-enrutamiento">🔗</a>   

8.  ##  ${\color{#04d220}Guard}$<a href="#guard">🛡️</a>
 - ${\color{#04d220}Crear\space guard\space}$<a href="#crear-guard">🛡️</a>
   - ${\color{#04d220}Crear\space guard\space con\space CanActivate}$<a href="#crear-guard-con-canactivate">🛡️</a>

9.  ##  ${\color{#04d220}Flat\space}$<a href="#flat">📁</a>

10.  ##  ${\color{#04d220}Pipes\space}$<a href="#pipes">🌀</a>
   -  ${\color{#04d220}Crear\space pipes\space pipes}$<a href="#crear-pipes">🌀</a>

11. ##  ${\color{#04d220}Directivas\space}$<a href="#pipes">📐</a>
   -  ${\color{#04d220}Directivas\space estructurales\space}$<a href="#directivas-estructurales">📐</a>
         -  ${\color{#04d220}Ejemplos}$<a href="#ejemplos-estructurales">📐</a>
   -  ${\color{#04d220}Directivas\space de\space atributo}$<a href="#directivas-de-atributo">📐</a>
         -  ${\color{#04d220}Ejemplos}$<a href="#ejemplos-atributo">📐</a>
   -  ${\color{#04d220}Directivas\space de\space eventos}$<a href="#directivas-de-eventos">📐</a>
   
      * ${\color{#04d220}Ejemplos\space eventos}$<a href="#ejemplos-eventos">📐</a>
         -  ${\color{#04d220}(click)}$<a href="#click">📐</a>
         -  ${\color{#04d220}(input)}$<a href="#input">📐</a>
         -  ${\color{#04d220}(submit)}$<a href="#submit">📐</a>
         - ${\color{#04d220}(mouseout)}$<a href="#mouseout">📐</a> 
         - ${\color{#04d220}(keyup)}$<a href="#keyup">📐</a> 
         -  ${\color{#04d220}(keydown)}$<a href="#keydown">📐</a> 
         -  ${\color{#04d220}(focus)}$<a href="#focus">📐</a>
         -  ${\color{#04d220}(blur)}$<a href="#blur">📐</a>    
  
  - ${\color{#04d220}Directivas\space personalizadas}$<a href="#directivas-personalizadas">📐</a>
  -  ${\color{#04d220}URL\space Event\space Binding }$<a href="#event-binding">📐</a>
    
     

<!-- ---------------1------------------------------------------------>
1. ## Iniciar el Proyecto

  - ${\color{blue}Modo \space basico  }$
```
ng new nombre-del-proyecto
```
 - ${\color{blue}Modo \space basico\space blanco }$
```
ng new nombre-del-proyecto --minimal
```
 - ${\color{blue}Con \space prefijo \space para \space especificar \space todos \space los \space componentes: }$  
 ```
ng new nombre-del-proyecto --prefix nombrePrefijo
```
 - ${\color{blue}Con \space  enrutamiento  \space y \space utilizando  \space SCSS \space en  \space su  \space totalidad  }$  
 ```
ng new AngularMaterial --routing --style=scss
```
 ### Instalar Angular Material

 - ${\color{blue}Dentro \space  del  \space proyecto}$

 ```
ng add @angular/material
```

 ### Cambiar directorio del proyecto

 ```
 ng new app-name --directory="FOLDER-NAME"

# Ejemplo
ng new myApp --directory="C:\New-Folder\"
``` 

2. ## Iniciar en servidor

```
ng serve -o
```
o
 ```
ng s -o
```
  - ${\color{blue}Definir \space en  \space package.json\space }$
```
"scripts": {
  "start": "ng serve"
}
# se inicia el servidor:
npm start
```

3. ## Cambiar puertos
```
ng serve --port 4200
``` 

4. ## Componentes
   ### Crear nuevo componente
```
ng g c componente-nombre
```
   ### Sin tests
```
ng g c componente-nombre --skip-tests
```
   ### Sin tests y estilos

```
ng g c nombre-componente --inline-style --skip-tests
```
   ### Sin template
```
ng g c mi-carpeta/componente-nombre --inline-template
```
  ### En otro directorio
```
ng g c mi-carpeta/componente-nombre
```
   ### Generar componente dentro del app-module
```
 ng g c components/componente-nombre --module=app.module
```
   ### Generar componente dentro de otro componente
```
 ng g c nombre-carpeta(componente)/nuevo-componente
```
   ### Sin importar en app-module 
```
 ng g c mi-carpeta/componente-nombre --skip-import
```
5. ## Modulos 
   ###  Crear nuevo modulo 
    ```
     ng g m modulo-nombre
    ```

   ### Especificar carpeta de destino
    ```
    ng g m mi-carpeta/modulo-nombre
    ```

   ###  Crear módulo con enrutamiento
    ```
     ng g m modulo-nombre --routing
    ```
   ### Crear componente en el modulo
    ```
    # 1º se debe crear el modulo
    ng g m Nombremodulo --routing

    # 2º se crear el componenete con el nombre modulo
    ng g c Nombremodulo/nombre-Componente --flat --skip-tests
    ```
   
6. ## Servicios
   ### Crear nuevo servicio
   ```
    ng g s nuevo-servicio --skip-tests
   ```
7. ## Routing
   ### Configurar enrutamiento
   ```
   # para crear routing dentro de un modulo
    ng g m nombreModuloRouting --flat
   ```
8. ## Guard
   ### Crear guard
   ```
   ng g guard nombreGuard2 --skip-tests
   ```
   #### Crear guard con CanActivate
   ```
    ng g guard nombreGuard --implements=CanActivate --skip-tests
   ```
9. ## flat
    
  - ${\color{blue}Crear \space dentro\space del\space directorio\space sin\space carpeta}$
```
ng g c mi-carpeta/componente-nombre --flat
```    
10. ## Pipes
    ### Crear pipes
    ```
    ng generate pipe nombre-pipe --skip-import
    ```
11. ## Directivas
    ### Directivas estructurales
   - \*ngIf
     - \ngIfElse 
   - \*ngFor
   - \*ngSwitch
  
   #### Ejemplos estructurales
   - \*ngIf (Condicional)
```html
<div *ngIf="mostrarElemento">
  Este elemento se mostrará si la variable mostrarElemento es verdadera.
</div>
```
   - \ngIfElse 
```html
<div *ngIf="isUserLoggedIn; else elseBlock">
      <h2>Bienvenido, Usuario</h2>
    </div>

    <ng-template #elseBlock>
      <h2>Por favor, inicia sesión</h2>
    </ng-template>
```
```TypeScript
 isUserLoggedIn = false;
 ```
  - \*ngFor (Repetición)
```html
<ul>
  <li *ngFor="let item of listaDeItems">
    {{ item }}
  </li>
</ul>
```
 - \*ngSwitch (Conmutación)
```html
<div [ngSwitch]="tipoDeContenido">
  <p *ngSwitchCase="'texto'">Este es un contenido de texto.</p>
  <div *ngSwitchCase="'imagen'">
    <img src="imagen.png" alt="Imagen">
  </div>
  <p *ngSwitchDefault>Contenido por defecto cuando no coincide ningún caso.</p>
</div>
``` 
   ### Directivas de atributo
   - [ngStyle] :Permite aplicar clases de manera condicional.
   - [ngClass] :Permite aplicar estilos de manera condicional.
   - [ngModel] :Utilizada para la vinculación bidireccional en formularios.
   
   #### Ejemplos atributo
   - [ngStyle]
 ```html
 <!-- Aplica un estilo de fondo rojo si la variable fondoRojo es verdadera -->
<div [ngStyle]="{'background-color': fondoRojo ? 'red' : 'transparent'}">
  Este elemento tiene fondo rojo si fondoRojo es verdadera.
</div>
 ```
   - [ngClass]
 ```html
<!-- Aplica la clase "resaltado" si la variable esVerde es verdadera -->
<div [ngClass]="{'resaltado': esVerde}">
  Este elemento tiene la clase "resaltado" si esVerde es verdadera.
</div>
 ```
   - [ngModel]
 ```html
<!-- Utiliza ngModel para vincular el valor del input a la variable nombre -->
<input [(ngModel)]="nombre" placeholder="Ingrese su nombre">

<!-- Muestra el valor vinculado -->
<p>Tu nombre es: {{ nombre }}</p>
 ```
   ### Directivas de eventos
  - (click): Captura eventos de clic.
  - (input): Captura eventos de entrada en elementos de formulario.
  - (submit): Captura eventos de envío de formularios.
  - (mouseover): Captura eventos cuando el mouse pasa por encima del elemento.
  - (mouseout): Captura eventos cuando el mouse sale del elemento.
  - (keyup): Captura eventos de liberación de tecla.
  - (keydown): Captura eventos de presión de tecla.
  - (focus): Captura eventos cuando un elemento recibe el foco.
  - (blur): Captura eventos cuando un elemento pierde el foco.
  
  #### Ejemplos eventos
   - ##### (click) 
```html
   <!-- Ejecuta la función handleClick cuando se hace clic en el botón -->
<button (click)="handleClick()">Haz clic</button>
``` 
```TypeScript
// En el componente TypeScript
handleChange(event: Event) {
  const inputElement = event.target as HTMLInputElement;
  console.log('Texto ingresado:', inputElement.value);
}
 ```
 -  ##### (input) 
```html
<!-- Ejecuta la función handleChange cuando se ingresa texto en el campo de entrada -->
<input (input)="handleChange($event)" placeholder="Ingresa texto">
``` 
```TypeScript
// En el componente TypeScript
handleChange(event: Event) {
  const inputElement = event.target as HTMLInputElement;
  console.log('Texto ingresado:', inputElement.value);
}
 ```
   - ##### (submit) 
```html
<!-- Ejecuta la función handleSubmit cuando se envía el formulario -->
<form (submit)="handleSubmit()">
  <!-- Otros campos del formulario -->
  <button type="submit">Enviar</button>
</form>
``` 
```TypeScript
// En el componente TypeScript
handleSubmit() {
  console.log('Formulario enviado');
  // Puedes realizar acciones adicionales aquí, como enviar datos al servidor.
}
 ```
- ##### (mouseover) 
```html
<div (mouseover)="handleMouseOver()">Pasa el mouse aquí</div>
```
-  ##### (mouseout) 
```html
<div (mouseout)="handleMouseOut()">Retira el mouse de aquí</div>
``` 
-  ##### (keydown) 
```html
<input (keydown)="handleKeyDown($event)" placeholder="Presiona una tecla">
``` 
-  ##### (focus) 
```html
<input (focus)="handleFocus()" placeholder="Enfócame">
``` 
-  ##### (blur) 
```html
<input (blur)="handleBlur()" placeholder="Pierdo el foco">

``` 
  ### Directivas personalizadas
  ```
  ng g d nombre-directiva --skip-import
  ```
  ```TypeScript
  import { Directive, ElementRef, HostListener, Input } from '@angular/core';

@Directive({
  selector: '[appNombreDirectiva]'
})
export class NombreDirectivaDirective {

  @Input() highlightColor: string = ''; // Color de resaltado por defecto

  constructor(private el: ElementRef) {}

  @HostListener('mouseenter') onMouseEnter() {
    this.highlight(this.highlightColor || 'yellow');
  }

  @HostListener('mouseleave') onMouseLeave() {
    this.highlight('');
  }

  private highlight(color: string) {
    this.el.nativeElement.style.backgroundColor = color;
  }
}
  ```
  ``` html
  <div appHighlight [highlightColor]="'cyan'">
  Pasa el ratón sobre mí
</div>
  ```
Explicaciòn[^2].

[^2]: @Directive({ selector: '[appHighlight]' }) define la directiva appHighlight y especifica que se puede aplicar a elementos con el atributo appHighlight.
@Input() highlightColor: string = ''; define una propiedad de entrada (highlightColor) que permite al usuario especificar un color de resaltado cuando utiliza la directiva.
@HostListener escucha eventos en el elemento que tiene la directiva. En este caso, escuchamos los eventos mouseenter y mouseleave y llamamos a las funciones correspondientes.
private highlight(color: string) es una función privada que cambia el color de fondo del elemento en función del color proporcionado.
  This is a second line.
  ###  Event Binding  
  👀  [URL Event binding](https://angular.io/guide/event-binding) 