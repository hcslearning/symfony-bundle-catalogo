# symfony-bundle-catalogo
Ejemplo de Bundle para Symfony 4 que entrega las funcionalidades para un Catálogo de Productos.

## Puntos clave

1) Para que automáticamente se lean las clases Entidad, se deben colocar las clases anotadas en la raíz del directorio del bundle dentro de una carpeta llamada Entity (no dentro de src/)
2) La configuración por defecto espera anotaciones para las entidades en Symfony 4
3) Dentro de composer.json se debe colocar la configuración de estabilidad mínima para que acepte bundles que no tienen releases, es decir, que extraigan el código de dev-master

