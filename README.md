<p align="center"> 
 <img src="assets/angular.png" width="6%">
</p>
<p align="center"> 
<img src="https://readme-typing-svg.demolab.com?font=Pixel Emulator&size=40&color=DD0031&center=true&vCenter=true&width=940&lines=Comandos+De+Angular🖥️" align="middle" alt=""  width="80%"/>
</p>

## ${\color{orange}📚Indice }$

 1. ###  ${\color{#04d220}Iniciar\space el \space Proyecto}$<a href="#iniciar-el-proyecto"> 🖲</a>
      1.1  ${\color{#04d220}Instalar\space  Angular\space Material}$<a href="#instalar-angular-material"> 🖲</a>

      1.2 ${\color{#04d220}Cambiar\space directorio\space del\space proyecto\space}$<a href="#instalar-angular-material"> 🖲</a>

2. ###  ${\color{#04d220}Iniciar\space en\space servidor}$<a href="#iniciar-en-servidor">🌐</a>

3. ###  ${\color{#04d220}Cambiar\space puertos}$<a href="#Cambiar-puertos">⚙️</a>

<!-- ---------------1------------------------------------------------>
1. ### Iniciar el Proyecto 

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
#### 1.1 Instalar Angular Material

 - ${\color{blue}Dentro \space  del  \space proyecto}$

 ```
ng add @angular/material
```

 #### 1.2 Cambiar directorio del proyecto

 ```
 ng new app-name --directory="FOLDER-NAME"

# Ejemplo
ng new myApp --directory="C:\New-Folder\"
``` 
<!-- ---------------------------------------------2-------------------- ----------------------------------------->
2. ### Iniciar en servidor

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
3. ### Cambiar puertos