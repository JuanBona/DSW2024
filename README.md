Desarrollo de Software
Este repositorio contiene todo el trabajo de desarrollo de software propuesto, implementado en React para el frontend y en Node.js con Express para el backend. Aquí se incluyen las funcionalidades principales, la arquitectura propuesta, y las configuraciones necesarias para desplegar el proyecto de manera eficiente.
### Repositorios
* [frontend app](https://github.com/felifernandez07/FrontEnd))
* [backend app](https://github.com/JuanBona/Trabajo-practico-DSW-UTN))

## Tema
### Descripción
Don Julio Tostadero de cafe es una plataforma en línea dedicada a la venta de café de alta calidad y productos relacionados. Ofrecemos granos de café de origen único, accesorios para café y productos gourmet. Nuestro objetivo es proporcionar a los amantes del café una experiencia de compra única y satisfactoria, brindando buenos productos y de calidad superior.

### Modelo
 ![CafeShop](https://github.com/JuanBona/Trabajo-practico-DSW-UTN/assets/155491172/aff995c9-37cb-4fb4-85e6-dae5a063249c)<br><br>
https://drive.google.com/file/d/1oMacCh4JopPpksrR-n-q04tDVllo_dPT/view?usp=drive_link



## Alcance Funcional 

### Alcance Mínimo

## Regularidad

| Req | Detalle |
| --- | --- |
| CRUD simple | 1. CRUD Categoría<br>2. CRUD Pedido<br>3. CRUD Persona<br>4. CRUD Producto |
| CRUD dependiente | 1. CRUD Administrador {depende de} CRUD Persona<br>2. CRUD Cliente {depende de} CRUD Persona |
| Listado + detalle | 1. Listado de productos filtrado por tipo de productos, muestra nombre y precio => detalle CRUD Producto<br>2. Listado de pedidos filtrado por rango de fecha, muestra número de pedido, fecha, estado y nombre del cliente => detalle muestra datos completos del pedido y del cliente |
| CUU/Epic | 1. Realizar un pedido de productos<br>2. Ver detalles de un pedido |

## Adicionales para la aprobación

| Req | Detalle |
| --- | --- |
| CRUD | 1. CRUD Categoría<br>2. CRUD Línea de Venta<br>3. CRUD Cliente<br>4. CRUD Producto<br>5. CRUD Venta<br>6. CRUD Valoración del Cliente<br>7. CRUD Marca<br>8. CRUD Tipo Persona |
| CUU/Epic | 1. Administrar valoraciones de productos y café<br>2. Registrar la compra de un cliente como consumidor final o empresa<br>3. Realizar el control de envíos del estilo retiro o envío |

Authors
@MaNNu017 49693
@guidoRodriguez13 47953
@JuanBona 47896
@felifernandez07
