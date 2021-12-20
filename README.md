# VueJs
Curso iniciado con la plataforma Vue Mastery, dónde crearé formularios, typescript y proyectos.

# Primer Lección
En index.html agrego una imagen, info y un link.

```
<div class="product-image">
  <img v-bind:src = "image">  
</div>

<div class="product-info">
  <h1>{{ product }}</h1>
  <a :href="link" target="_blank">More products like this</a>
</div>

<script src="https://cdn.jsdelivr.net/npm/vue@2.5.13/dist/vue.js"></script>
<script src = "main.js"></script>
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
