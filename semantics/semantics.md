!SLIDE center transition=scrollUp

# Semântica #

![Semântica](semantics.png)

!SLIDE bullets incremental

# Estrutura <=> Significado #

* elementos e atributos revisados
* novos elementos
* RDFa
* _microdata_
* _microformats_



!SLIDE

# `doctype` #

!SLIDE

    @@@html
    <!DOCTYPE html
     PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
     "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

!SLIDE bullets

# Modos de renderização #

* _quirks mode_
* _almost standards mode_
* _standards mode_

!SLIDE bullets

# Modos de renderização #

* _quirks mode_
* _limited quirks mode_
* _no quirks mode_

!SLIDE

    @@@html
    <!DOCTYPE html
     PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
     "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

!SLIDE

    @@@html
    <!DOCTYPE html>



!SLIDE

# `<html>` #

!SLIDE

    @@@html
    <html xmlns="http://www.w3.org/1999/xhtml"
          lang="pt"
          xml:lang="pt">

!SLIDE bullets

* `xmlns="http://www.w3.org/1999/xhtml"`: padrão
* `lang="pt"` == `xml:lang="pt"`

!SLIDE

    @@@html
    <html lang="pt">





!SLIDE

# `<head>` #

!SLIDE

# `<meta>` #

    @@@html
    <meta http-equiv="Content-Type"
          content="text/html; charset=utf-8">

!SLIDE

# `<meta>` #

    @@@html
    <meta charset="utf-8" />





!SLIDE

# Links #


!SLIDE bullets

# Links: vários tipos, vários usos #

* folha de estilo
* _feed_
* tradução
* pdf
* outro post
* ...

!SLIDE bullets

# Tipos de links #

* _links_ (`link`)
* _hyperlinks_ (`a`)

.notes `link` aponta para recursos externos, usados pelo documento atual de alguma maneira
.notes o comportamento de `link` depende em sua relação `rel`
.notes `a` aponta para outros documentos

!SLIDE bullets incremental

# `rel` #

* `stylesheet`
* `alternate`
* `archives`
* `external`
* `start`, `prev`, `next`
* `icon`
* ...





!SLIDE bullets

# Novos elementos #

`<section>`, `<nav>`, `<article>`, `<aside>`, `<hgroup>`,
`<header>`, `<footer>`, `<time>`, `<mark>`

!SLIDE

# Exemplo: `article` & `time` #

    @@@html
    <div class="talk">
      <h2>Data da palestra</h2>
      <p class="talk-date">
        30 de Março de 2011
      </p>
    </div>

!SLIDE

# Data & hora #

    @@@html
    <article>
      <h2>Data da palestra</h2>
      <time datetime="2011-03-30">
        30 de Março de 2011
      </time>
    </article>

!SLIDE

# Data & hora #

    @@@html
    <article>
      <h2>Data da palestra</h2>
      <time datetime="2011-03-30">
        Hoje
      </time>
    </article>




!SLIDE

# Muito mais... #
