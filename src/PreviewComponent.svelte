<script>
    import { createEventDispatcher } from 'svelte';
  
    const dispatch = createEventDispatcher();
  
    export let noticia;
  
    function verMas() {
      dispatch('ver-noticia', noticia);
    }
  </script>
  
  <div class="preview">
    <h2>{noticia.titulo}</h2>
    <p>{noticia.preview}</p>
    <button on:click={verMas}>Ver más</button>
  </div>
  
  
  