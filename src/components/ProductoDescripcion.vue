<template>
  <section  class="dos-columnas">
    <div class="vid">
      <video
        id="vid1"
        width="380"
        height="215"
        class="video-js vjs-default-skinnp flex_row"
        preload="auto"
        poster="..//assets/poster.png"
        controls
        data-setup="{}"
        copyright="cc-0"
      >
        <source src="..//assets/video.mp4" type="video/mp4" />
        <p class="vjs-no-js">
          To view this video please enable JavaScript, and consider upgrading to
          a web browser that
          <a href="http://videojs.com/html5-video-support/" target="_blank">
            supports HTML5 video
          </a>
        </p>
      </video>
    </div>

    <div class="texto">
      
      <ul>
        <li>
          El coche clásico y el milagro espacial de Gran Bretaña. Ahora también
          de PLAYMOBIL: figuras y accesorios de una escena londinense de los
          años 70.
        </li>
        <li>
          Dimensiones: 18,5 x 10 x 8 cm. (largo x ancho x alto). Recomendado
          para edades comprendidas entre los cinco y los noventa años.
          Advertencia. Peligro de asfixia. Piezas pequeñas. No apto para niños y
          niñas menores de 3 años.
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {};
</script>


<style scoped>
#producto-descripcion {
  justify-content:center;
  margin: 1em;
}

.vid {
  display: flex;
  flex-direction: row;
  position: relative;
  width: 31.25rem;
  justify-content: center;
}

.texto {
  position: relative;
  margin-top:1em;
  width: 31.25rem;
  justify-content:left;
  color:darkblue;
}

</style>