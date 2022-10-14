<h1 align="center"> Busqueda por departamento </h1>

Componente que renderiza resultados de un departamento escogido en un bloque de selección

![department_search](https://user-images.githubusercontent.com/95322919/195915639-033685af-352e-4d18-9c4e-e8108006d4fb.png)

____________
## :hammer:Configuración del proyecto

- :pushpin: `Paso 1 - Configuración Básica`: 
  Asegurarse que esta en el ambiente correcto de vtex

- :pushpin: `Paso 2 - Clonación del repositorio`: 
  Ingresar al repositorio estandar de vtex- react [<sub>https://github.com/vtex-apps/react-app-template</sub>] 
- :pushpin: `Paso 3 - Editar el Manifest.json`: 
  Se sugiere que se cambien los valores del vendor, versión y name si fuese necesario, los valores actuales son
  
  ```ruby
    "vendor": "itglobers",
    "name": "custom-department-search",
    "version": "0.0.1",
  ```
  Si desea cambiar estos valores se recomienda:
  
  :mag:"vendor": "nombre_del_la_tienda"<br>
  :mag:"version": "version_del_componente_actual"
  ________

## :key:Dependencia
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
