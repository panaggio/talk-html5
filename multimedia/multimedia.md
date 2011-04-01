!SLIDE transition=scrollUp center

# Multimídia #

![Multimídia](multimedia.png)

!SLIDE

# Motivação #
## Vídeo e áudio se tornaram cidadãos de primeira ordem na web ##

!SLIDE bullets incremental

# Suporte a áudio e vídeo #

* QuickTime
* RealPlayer
* Flash
* ...

!SLIDE

# Suporte a `audio` e `video` #

!SLIDE

# `video` #

    @@@html
    <video src="html5.theora.ogv" width="640"
           height="360" controls="controls">
    </video>

!SLIDE

    @@@html
    <video id="video" width="640"
           height="360" controls="controls" >
      <source src="html5.webm"
              type="video/webm" />
      <source src="html5.theora.ogv"
              type="video/ogg;
              codecs=&quot;theora, vorbis&quot;" />
      <source src="html5.mp4" type="video/mp4" />
    </video>

!SLIDE

<div class="video">
  <video id="video" width="640" height="360" controls="controls" preload="metadata" >
  <source src="http://videos-cdn.mozilla.net/serv/marketing/firefox4/WN-Desktop-V2_640.webm" type="video/webm" />
  <source src="http://videos-cdn.mozilla.net/serv/marketing/firefox4/WN-Desktop-V2_640.theora.ogv" type="video/ogg; codecs=&quot;theora, vorbis&quot;" />
  <source src="http://videos-cdn.mozilla.net/serv/marketing/firefox4/WN-Desktop-V2_640.mp4" type="video/mp4" />
  </video>
</div>
