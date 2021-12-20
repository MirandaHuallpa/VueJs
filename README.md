# VueJs
Curso iniciado con la plataforma Vue Mastery, dónde crearé formularios, typescript y proyectos.

En index.html agrego una imagen.

```
<div class="product-image">
  <img v-bind:src = "image">  
</div>
```

<p>En main.js:</p>

```
var app = new Vue ({
  el: '#app',
  data: {
      product: 'Socks',
      image: 'assets/vmSocks-green-onWhite.jpg',
      link: 'https://www.amazon.com/s/ref=nb_sb_noss?url=search-alias%3Daps&field-keywords=socks'
  }
})
```
