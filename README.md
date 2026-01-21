#
                                                       Bienvenido a DriveStore

                                   Domina el Terreno de Juego con el calzado que marca la diferencias
                                                      Envío a todo México  🇲🇽


![DriveStore](https://github.com/user-attachments/assets/8de4b6f3-e32b-4566-ac6b-a762c7238ff1)

##Descripción
Crear una pagina wed donde se pueda realizar compras para mi pagina wed llamada DriveStore por la cual realizo mis ventas de calzado de futból donde se ofrece modelo de retros y actuales 100% origianeles contaando con envio a todo La republica Mexicana.

##Problematica
DriveStore es una página web de comercio electrónico dedicada a la venta de tenis de fútbol retros y recientes. Su principal fuente de venta es mediantes redes sociales (facebook,messenger,instagram), ofreciendo una plataforma organizada, moderna y accesible para clientes de todo México.

## Valor Agregado del Framework

Al utilizar de React permite que DriveStore tenga una interfaz dinámica y reactiva donde los cambios en el catálogo, las tallas y el carrito de compras se actualizan en tiempo real la página.Para manejo del estado, la información del pedido se mantiene sincronizada en toda la aplicación, ofreciendo una experiencia más rápida, clara y eficiente en comparación con un sitio web tradicional.



##Requerimientos Funcionales
Visualizar el catálogo de tenis de fútbol con imágenes, precios y tallas disponibles.
Filtrar los productos por marca, talla y tipo de superficie.
Agregar y eliminar productos del carrito de compras de manera interactiva.
Visualizar el resumen de la compra con el total y la información de envío.
Registrar los datos del usuario para completar y confirmar el pedido.



##Requerimientos No Funcionales (El "Cómo funciona")



<img width="738" height="323" alt="Captura de pantalla 2026-01-21 133804" src="https://github.com/user-attachments/assets/23f00626-7bf8-45fc-9c4d-486a2d8c06bd" />

Tecnologías y Herramientas del Ecosistema


##Manejo de Estado Global

Context API (React)
Se utilizará Context API para manejar el estado global de la aplicación, como el carrito de compras y los productos seleccionados. Esta solución es adecuada por la escala del proyecto, ya que permite compartir el estado entre componentes sin necesidad de usar librerías externas más complejas como Redux.

##Consumo de Datos

Fetch API
Los datos de los productos (tenis, precios, tallas y disponibilidad) se obtendrán mediante Fetch API desde un archivo JSON local o una API simulada. Esto permite una integración sencilla y suficiente para el alcance del proyecto.

##Estilizado

CSS con Flexbox y Grid / Tailwind CSS
Se utilizará CSS moderno (Flexbox y Grid) o Tailwind CSS para crear una interfaz responsive, limpia y adaptable a dispositivos móviles y de escritorio.

##Despliegue

Vercel
La aplicación será desplegada en Vercel, ya que ofrece una integración sencilla con proyectos en React y repositorios de GitHub, permitiendo un despliegue rápido y confiable.

##Diagrama de Flujo

<img width="1024" height="1536" alt="Diagrama del proceso de compra online" src="https://github.com/user-attachments/assets/004165e0-a6f0-4324-a7c2-dce56c102e08" />


Primero, el usuario ingresa a la página DriveStore y puede visualizar el catálogo de tenis de fútbol disponible. Después, tiene la opción de filtrar los productos por marca, talla o tipo de superficie, lo que hace que el catálogo se actualice de manera automática sin necesidad de recargar la página.

Una vez que el usuario encuentra el producto que desea, lo selecciona y hace clic en el botón “Agregar al carrito”. En ese momento, el estado global del carrito se actualiza, lo que provoca que el componente del carrito y el resumen de la compra se rendericen nuevamente. Finalmente, el usuario puede ver en tiempo real el total a pagar y la información del envío, obteniendo una experiencia de compra rápida, clara y fluida.
