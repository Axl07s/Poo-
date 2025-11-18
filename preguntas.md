1. ¿Qué ventajas observas en la versión orientada a objetos?
Encapsulamiento: Los datos del producto (nombre, precio, cantidad) están protegidos dentro de la clase y solo se accede a ellos mediante métodos. Esto evita errores y hace el código más seguro.
Modularidad: Cada clase cumple una función específica. El programa se divide en piezas independientes y fáciles de entender.
Reutilización: La clase Producto puede utilizarse en otros programas sin cambiar su código.
Escalabilidad: Es más sencillo extender el programa: agregar más atributos, funciones o nuevas clases (por ejemplo, Tienda, Cliente, Factura, etc.).
Legibilidad: El código se parece más a cómo pensamos el problema en la vida real: productos, tienda, inventario…

2. ¿Qué parte del código resultó más clara o fácil de mantener?
La parte más clara es la clase Producto, porque:
Reúne toda la información relacionada con un producto.
Tiene métodos que realizan operaciones específicas (calcularTotal, mostrarInfo).
Permite crear múltiples productos sin repetir código.
Además, en TiendaApp es fácil entender qué hace cada parte: registrar productos, mostrarlos y sumar el total.

3. ¿Cómo podriás extender el programa para manejar más productos?
Hay varias opciones:
Cambiar el tamaño del arreglo
Reemplazar new Producto[2] por new Producto[n], donde n se pida al usuario.
Usar un ArrayList
Permite agregar productos dinámicamente sin definir un límite fijo.
Ejemplo:
ArrayList<Producto> productos = new ArrayList<>();
3. Crear una clase Tienda
La tienda tendría una lista de productos y métodos para:
agregar productos
mostrar el inventario
calcular el total general
buscar productos
eliminar productos
Esto convierte el sistema en algo más cercano a un programa real.

4. ¿Podrías agregar una clase Tienda que contenga los productos y calcule el total?
Sí, es posible y además es una muy buena práctica dentro de la programación orientada a objetos.
Al crear una clase Tienda, se logra organizar mejor el programa, ya que esta clase se encargaría de administrar todo lo relacionado con el inventario. La tienda podría tener internamente una lista o arreglo de productos, y ofrecer métodos específicos para realizar acciones comunes, como:
Agregar productos al inventario.
Mostrar todos los productos registrados.
Calcular el total general del inventario, sumando el total individual de cada producto.
Facilitar la expansión del programa, permitiendo más funcionalidades como buscar, eliminar o actualizar productos.
Con esta clase adicional, la estructura del programa se vuelve más modular y clara:
La clase Producto representa un producto individual, mientras que la clase Tienda representa el conjunto de productos y las operaciones que involucran a varios de ellos. Esto refleja mejor la forma en que funciona una tienda real y facilita mucho el mantenimiento del código y futuras extensiones.

