!SLIDE

# Detectando HTML 5 #

!SLIDE

# Modernizr #

## Biblioteca para detecção de suporte a HTML 5 e CSS 3 ##

!SLIDE bullets

# Modernizr #

* software livre (MIT license)
* atualizada muito frequentemente
* fácil de usar

!SLIDE

    @@@html
    <!DOCTYPE html>
    <html>
      <head>
        ...
        <script src="modernizr.min.js"></script>
        ...
      </head>
      ...
    </html>

!SLIDE

    @@@javascript
    if (Modernizr.canvas) {
      // use canvas
    } else {
      // display a message
      // or use fallback
    }
