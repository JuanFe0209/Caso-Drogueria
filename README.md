Diagramas: https://drive.google.com/drive/folders/1G9svfLmhWbe5t3NGmYDZmDVSW0XN_alr?usp=sharing

Singleton: La implementación del Singleton se realizó en la clase DrogueriaSingleton. El método __new__ se sobrescribió para garantizar que solo se creara una instancia de la clase. 
Cuando se crea una instancia de DrogueriaSingleton, se verifica si ya existe una instancia y, si es así, se devuelve esa instancia en lugar de crear una nueva.
Esto asegura que solo haya una única instancia en el programa.

Builder: La implementación del Builder se realizó en la clase PedidoBuilder. Esta clase se encarga de construir objetos de la clase Pedido.
Proporciona métodos para establecer los atributos del pedido, como el ID del pedido, la fecha y el ID del cliente, de manera fluida. 
Luego, el método build crea y devuelve un objeto Pedido con los valores establecidos.

Prototype: La implementación del Prototype se realizó en la clase Producto. Se creó un método clonar que crea una copia exacta del objeto actual. 
Esto permite clonar un producto existente para crear uno nuevo con los mismos atributos, pero con la capacidad de modificarlos según sea necesario. 
En el ejemplo, se crea un nuevo producto clonando uno existente y luego modificando algunos de sus atributos.
