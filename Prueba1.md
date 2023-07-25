# Prueba1

1. Dado el siguiente bloque de codigo describe lo que sucederia en la pantalla.
     
  ```html
  <html>
    <head>
      <title>Prueba1</title>
    </head>
    <body>
      <h1>Prueba1</h1>
      <p>Prueba1</p>
    </body>
  </html>
  ```
  ```css
  h1 {
    color: red;
  }
  ```
2. Cuales son 3 principales tipos de selectores que existen en CSS y como se diferencian entre si.
3. Cual es la diferencia entre una clase y un id en CSS.
4. Tengo este codigo, que estilos debo agregar para que las cajas queden centradas en la pantalla.
  
  ```html
  <html>
    <head>
      <title>Prueba1</title>
    </head>
    <body>
      <div class="caja">Caja 1</div>
      <div class="caja">Caja 2</div>
      <div class="caja">Caja 3</div>
    </body>
  </html>
  ```
5. Si quiero que las cajas tengan un ancho de 100px y un alto de 100px, que estilos debo agregar.
6. Como harias replicar esta imagen usando HTML y CSS.  
  ![Imagen](/capturaPrueba.png)
1. Y si ahora lo quiero centar en la mitad de la pagina, que es lo que le agregarias ?
2. Como harias para que cuando pase el mouse por encima de la caja, esta cambie de color.
3. Que etiquetas HTML conoces para agregar texto a una pagina web.
4.  Dibuje la posible salida de este fragmento de codigo.
    ```html
    <html>
      <head>
        <title>Prueba1</title>
      </head>
      <body>
        <div class="caja">Caja 1</div>
        <div class="caja">Caja 2</div>
        <div class="caja">Caja 3</div>
      </body>
    </html>
    ```
    ```css
    body {
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
    }
    .caja {
      width: 100px;
      height: 100px;
      background-color: red;
      margin: 10px;
    }
    ```
5.  Cual es la diferencia entre padding y margin. Puede utilizar un ejemplo o dibujo para explicarlo.