<script>
    import PreviewComponent from "./PreviewComponent.svelte";
    //Definimos el objeto
    let noticias = [
    {
        titulo: 'Un nuevo estudio revela una forma efectiva de prevenir el estrés laboral',
        preview: 'La investigación sugiere que un aumento de actividades de ocio puede mejorar el bienestar en el trabajo.',
        contenido: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
    },
    {
        titulo: 'Descubren una nueva especie de ave en la selva amazónica',
        preview: 'La nueva especie de ave fue encontrada en una zona remota de la selva amazónica y su descubrimiento ha generado gran interés entre los expertos.',
        contenido: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
    },
    {
        titulo: 'El nuevo sistema de transporte público de la ciudad recibe críticas',
        preview: 'Los usuarios se quejan de largos tiempos de espera y retrasos en los horarios, mientras que los operadores aseguran estar trabajando para mejorar el servicio.',
        contenido: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
    },
    {
        titulo: 'La nueva película de ciencia ficción promete ser todo un éxito',
        preview: 'La crítica especializada alaba la calidad del guión y los efectos especiales, y el público espera ansioso su estreno.',
        contenido: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.'
    },
    {
        titulo: 'El equipo de fútbol local logra un importante triunfo en casa',
        preview: 'El equipo local consiguió una victoria por goleada en su propio estadio, y los aficionados celebraron la hazaña en las calles de la ciudad.',
        contenido: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim'}
    ]
</script>


<div class="portada">
    {#each noticias as noticia}
      <div class="preview">
        <h2>{noticia.titulo}</h2>
        <p>{noticia.preview}</p>
      </div> 
    {/each}
  </div>


