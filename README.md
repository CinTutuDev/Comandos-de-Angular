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

3. ##  ${\color{#04d220}Cambiar\space puertos}$<a href="#Cambiar-puertos">⚙️</a>
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


1.  ##  ${\color{#04d220}Guard}$<a href="#guard">🛡️</a>

9.  ##  ${\color{#04d220}flat\space}$<a href="#flat">📁</a>

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
<!-- ---------------------------------------------2-------------------- ----------------------------------------->
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

<!-- -------------------------------------------------------------3-------------------- -->
3. ## Cambiar puertos
```
ng serve --port 4200
``` 
<!-- ------------------------------------------------------------4-------------------- -->
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
<!-- -----------------------------------------------------------5-------------------- -->

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