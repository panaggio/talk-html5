!SLIDE transition=scrollUp

# Introdução #

!SLIDE bullets

# História #

* 1990: HTML
* 1995: HTML 2.0
* 1997: HTML 3.2
* 1999: HTML 4.01
* 2000: XHTML 1.0
* 2001: XHTML 1.1
* HTML 5

!SLIDE bullets incremental

# HTML #

* Estrutura
* Apresentação
* Integração: DOM, APIs, JavaScript, ...

.notes Agora, é também como a estrutura e apresentação iteragem com JavaScript, via DOM
.notes Não é só a definição da tag: há APIs que podem ser utilizadas para inúmeras coisas, como detectar suporte a certas partes do padrão, executar ações sobre os elementos, ...

!SLIDE quotation

> APIs e DOM: partes fundamentais da especificação

!SLIDE

> Facilitar a inclusão e manuseio de conteúdo gráfico e multimídia sem a necessidade de API ou plugins proprietários

.notes Detalhamento do processamento necessário para processa documentos inválidos, de forma que erros de sintaxe sejam trqatados de maneira uniforme pelos vários browser e user agentes

!SLIDE bullets

# HTML5: tecnologia central da web #

* Revisão mais recente do padrão HTML
* Ainda em desenvolvimento
* Muita coisa pronta
* Muita coisa por vir

!SLIDE bullets

# Objetivos #
* Melhorar suporte a multimídia / tecnologia
* Manter simplicidade do entendimento

!SLIDE bullets

# Demo #

* [Runfield](https://mozillademos.org/demos/runfield/demo.html)
* [HTML5 Poster](https://mozillademos.org/demos/dashboard/demo.html)

!SLIDE
# Dive Into HTML5 #
## "5 coisas que você deveria saber" ##

!SLIDE bullets

# 1. Não é uma grande e única coisa #

* coleção de pequenas *features* individuais
* detecção de suporte das *features*, e não de HTML 5

!SLIDE bullets

# 2. Não é necessário jogar nada fora #

* HTML4 é o maior sucesso entre linguagens *markup*
* HTML5 foi construído em cima desse sucesso
* HTML4 é compatível (em sua maior parte) com HTML5
* Se algo funciona com HTML4, vai funcionar em HTML5

!SLIDE bullets incremental

# 3. É fácil começar #

1. Trocar o `doctype`
2. Fim

!SLIDE

    @@@html
    <!DOCTYPE html>
    <html lang='pt'>
      <head>
        <title>HTML5: é fácil começar</title>
      </head>
      <body>
        <h1>HTML5: é fácil começar</h1>
        <p>Definido o
        <code><!DOCTYPE html></code>,
        você está pronto para utilizar tudo
        o que HTML5 pode oferecer</p>
        <canvas>...</canvas>
      </body>
    </html>

.notes Antigamente, podia ser complicado definir o `doctype`, porque eles eram muito complicados e cheios de atributos
.notes em HTML5, a definição do `doctype` é única e simples

!SLIDE bullets

# Novo `doctype` #

* Não quebra nada definido em HTML4
* Permite uso das novidades

!SLIDE bullets

# 4. Já funciona #

* Muitas partes do padrão estão prontas
* Muitas partes já estão implementadas em vários browsers

!SLIDE bullets incremental

# Navegadores #

* Firefox
* Safari
* Chrome
* Opera
* navegadores móveis (Android, iPhone, ...)
* IE

!SLIDE bullets

# Navegadores #

* Suporte é razoavelmente bem conhecido e documentado
* Emulação de características novas em navegadores "antigos"

.notes JavaScript, _plugins_, biblitoecas ajudam muito nisso

!SLIDE bullets

# 5. Chegou pra ficar #

* "Futuro da Web"
* Planejamento de longo prazo
* Fusão de esforços

!SLIDE quotation

> "Today the Director announces that when the XHTML 2 Working Group charter expires as scheduled at the end of 2009, the charter will not be renewed. By doing so, and by increasing resources in the HTML Working Group, **W3C hopes to accelerate the progress of HTML5 and clarify W3C’s position regarding the future of HTML.**"
