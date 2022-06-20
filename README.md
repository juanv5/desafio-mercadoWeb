# Desafio-MercadoWeb

## Instrucciones

Ingresar a la terminal y usar los comandos:

- `npm init`
- `npm install express --save`
- `npm install --save bootstrap`
- `npm install --save jquery`
- `npm install --save express-handlebars`
- `git init`
- `node index`

Abrir el servidor en [http://localhost:3000] para cargar las imagenes

## Requerimientos

1. Crear una ruta raíz que al ser consultada renderice una vista con un parcial
“Dashboard” enviándole en el render un arreglo con los nombres de los productos. Se
recomienda que estos coincidan con las imágenes de cada producto.
2. Incluir en la vista un parcial que contenga el menú del sitio web y sea renderizado
antes del Dashboard.
3. Crear un parcial “producto” que contenga el template correspondiente a la
presentación de cada producto en el Dashboard y reciba como parámetro el nombre
del producto.
4. Crear un parcial para la sección principal en donde se renderice un helper con el
mensaje de bienvenida y se realice una iteración para renderizar un parcial
“producto” pasándole como argumento el nombre de cada producto.
5. Consumir los códigos fuentes de Bootstrap y jQuery a través de rutas o middlewares
creados en el servidor. Estas dependencias deben ser instaladas con NPM.

### Dependencias

1. bootstrap: ^5.1.3
2. express: ^4.18.1
3. express-handlebars: ^6.0.6
4. jquery: ^3.6.0

### Integrantes

- Maria Jose Ramirez [http://github.com/mjramirez1]
- Juan Vega Díaz [http://github.com/juanv5]
