<h1 align="center"> Busqueda por departamento </h1>

Componente que renderiza resultados de un departamento escogido en un bloque de selección

![department_search](https://user-images.githubusercontent.com/95322919/195915639-033685af-352e-4d18-9c4e-e8108006d4fb.png)

____________
## :hammer:Configuración del proyecto

- :pushpin: `Paso 1 - Configuración Básica`: 
  Asegurarse que esta en el ambiente correcto de vtex
- :pushpin: `Paso 2 - Clone estos archivos` con el link proporcionado en el repositorio 
- :pushpin: `Paso 3 - Instalacion de nodos de react`: 
  Ingresar a la carpeta de react ejecutando el comando en consola ```$ cd react```
  y dentro de esta instalar lo siguiente: <br>
  :pencil2:`1` Nodos de react ejecutando en consola el comando ```$ yarn``` <br>
  :pencil2:`2` Paquete `css-handles` para los estilos basicos ```$ @vtex/css-handles```
- :pushpin: `Paso 4 - Volver a carpeta principal del proyecto y linkear app a su Tienda`: 
  Ejecute comando en consola ```$ vtex link```
  ________
## :key: Listado de apps que están funcionando en la tienda
  1.  "vtex.css-handles": "0.x",
  2.  "vtex.store-graphql": "2.x",
  3.  "vtex.store-components": "3.x"
__________
## :key:Dependencias

1. Store GraphQl

```ruby
  "dependencies": 
  {
    "vtex.store-graphql": "2.x"
  }
```
2. Store-theme

```ruby
  "dependencies": 
  {
    "itglobers.custom-department-search": "0.x"
  }
```

## :key:Manera de llamar al componente: 
Ejemplo:
```
"flex-layout.row#department-search":{
    "children":["department-search"]
    }
```

## :black_nib:Autor

 [<sub>Génesis Pinto</sub>](https://github.com/genesispinto) 
