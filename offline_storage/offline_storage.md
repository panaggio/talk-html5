!SLIDE transition=scrollUp center

# _Offline_ & Armazenamento #

![Offline & Armazenamento](offline_storage.png)

!SLIDE bullets

# Motivação #

* Iniciar _apps_ mais rapidamente
* Trabalhar _offline_

!SLIDE bullets

# _Offline_ & Armazenamento #

* App Cache
* Web Storage
* WebDB
* WebSimpleDB/IndexedDB
* File API



!SLIDE

# App Cache #

!SLIDE bullets

# Web App: lista de URLs #

* html
* css
* js
* Imagens
* ...

!SLIDE bullets

# `manifest`: lista de URLs #

* html
* css
* js
* Imagens
* ...

!SLIDE

    CACHE MANIFEST
    /html5.css
    /html5.js
    /umamao.jpg
    ...

!SLIDE

    @@@html
    <!DOCTYPE html>
    <html manifest='/html5.manifest'>
      <head>...</head>
      <body>...</body>
    </html>



!SLIDE

# Web Storage #

!SLIDE bullets

# Armazenamento em aplicações desktop #

* xml
* bancos de dados
* arquivos binários
* ...

!SLIDE bullets

# Armazenamento local em aplicações web #

* Cookies

!SLIDE bullets

# Cookies: problemas #

* _overhead_ nas requisições
* tráfego de dados não encriptados
* tamanho máximo de 4KB

!SLIDE bullets

# Exemplos de alternativas #

* IE userData
* Flash (AMASS, ...)
* Gears
* dojox.storage

!SLIDE bullets

# Alternativas: problemas #

* Dependente de navegador
* Dependente de plugin
* Dependente de extensão
* Gerenciar alternativas é muito complicado
* Herança dos problemas respectivos

!SLIDE bullets

# Web Storage #

* bastante espaço
* local
* persistente
* transferências zero
* armazenamento chave/valor
* nativo

!SLIDE

# `localStorage` #

    @@@javascript
    interface Storage {
      getter any getItem(in DOMString key);
      setter creator void setItem(
        in DOMString key, in any data
      );
      //...
    };

!SLIDE

    @@@javascript
    var foo = localStorage.getItem('bar');
    // ...
    localStorage.setItem('bar', foo);

!SLIDE

    @@@javascript
    var foo = localStorage['bar'];
    // ...
    localStorage['bar'] = foo;




!SLIDE

# WebDB, WebSimpleDB/IndexedDB #

!SLIDE bullets

# WebDB, WebSimpleDB/IndexedDB #

* SQLite dentro do navegador
* Acessível via JavaScript + SQL




!SLIDE

# File API #

!SLIDE

# File API #

## Acesso a arquivos locais ##

!SLIDE

    @@@html
    <input type='file'
           id='input'
           onchange='handleFiles(this.files)'>

!SLIDE

    @@@javascript
    var elem = document.getElementById('input');
    elem.addEventListener(
      'change', handleFiles, false
    );

    function handleFiles() {
      var files = this.files;
      //...
    }

!SLIDE

# [Demo](http://html5demos.com/file-api) #
