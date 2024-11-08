# Proyecto de Desarrollo de Software

Este repositorio contiene el trabajo de desarrollo de software realizado para una plataforma de venta en línea, implementada en **React** para el frontend y en **Node.js con Express** para el backend. En este repositorio, encontrarás las funcionalidades principales, la arquitectura propuesta y las configuraciones necesarias para desplegar el proyecto de manera eficiente y escalable.

### Repositorios
* [Frontend App](https://github.com/felifernandez07/FrontEnd)
* [Backend App](https://github.com/JuanBona/Trabajo-practico-DSW-UTN)

## Tema
**Don Julio Tostadero de Café** es una plataforma en línea dedicada a la venta de café de alta calidad y productos relacionados. Ofrecemos granos de café de origen único, accesorios y productos gourmet para los amantes del café que buscan una experiencia de compra única y satisfactoria, con productos de calidad superior.

### Modelo de la Plataforma
![CafeShop](https://github.com/JuanBona/Trabajo-practico-DSW-UTN/assets/155491172/aff995c9-37cb-4fb4-85e6-dae5a063249c)

[Ver modelo en Google Drive](https://drive.google.com/file/d/1oMacCh4JopPpksrR-n-q04tDVllo_dPT/view?usp=drive_link)

## Alcance Funcional 

### Alcance Mínimo

| Requisito           | Descripción |
|---------------------|-------------|
| **CRUD simple**     | 1. CRUD de Categoría<br>2. CRUD de Pedido<br>3. CRUD de Persona<br>4. CRUD de Producto |
| **CRUD dependiente**| 1. CRUD de Administrador (depende de CRUD Persona)<br>2. CRUD de Cliente (depende de CRUD Persona) |
| **Listado + Detalle** | 1. Listado de productos filtrado por tipo, mostrando nombre y precio => Detalle en CRUD Producto<br>2. Listado de pedidos filtrado por fecha, mostrando número de pedido, fecha, estado y nombre del cliente => Detalle con información completa del pedido y cliente |
| **CUU/Epic**        | 1. Realizar un pedido de productos<br>2. Ver detalles de un pedido |

## Funcionalidades Adicionales para la Aprobación

| Requisito          | Descripción |
|--------------------|-------------|
| **CRUD**           | 1. CRUD de Categoría<br>2. CRUD de Línea de Venta<br>3. CRUD de Cliente<br>4. CRUD de Producto<br>5. CRUD de Venta<br>6. CRUD de Valoración del Cliente<br>7. CRUD de Marca<br>8. CRUD de Tipo de Persona |
| **CUU/Epic**       | 1. Administrar valoraciones de productos y café<br>2. Registrar compras para cliente final o empresa<br>3. Gestionar el control de envíos o retiros |

## Autores

- @MaNNu017 (49693)
- @guidoRodriguez13 (47953)
- @JuanBona (47896)
- @felifernandez07
