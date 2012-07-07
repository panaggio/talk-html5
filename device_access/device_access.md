!SLIDE transition=scrollUp center

# Acesso a dispositivos #

![Acesso a dispositivos](device_access.png)

!SLIDE

# Motivação #

## Dispositivos possuem inúmeros recursos úteis e interessantes ##

!SLIDE bullets

# Novos recursos explorados #

* GPS/bússola
* câmera
* microfone
* agenda de contatos
* ...





!SLIDE

# Geolocalização #

!SLIDE bullets

# Geolocation API #

* Compartilhamento de geolocalização
* Usuário tem controle sobre a informação

!SLIDE

# `geolocation` #

    @@@javascript
    function getLocation(geoCallback) {
      navigator.geolocation.getCurrentPosition(
        geoCallback
      );
    }


!SLIDE

    @@@javascript
    function geoCallback(position) {
      var coords = position.coords;

      var latitude = coords.latitude;
      var longitude = coords.longitude;
      var accuracy = coords.accuracy;

      var altitude = coords.altitude;
      var altaccuracy = coords.altitudeAccuracy;

      var heading = coords.heading;
      var speed = coords.speed;
      // ...
    }
