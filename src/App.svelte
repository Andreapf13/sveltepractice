<script>
    import PreviewComponent from "./PreviewComponent.svelte";
    //Definimos el objeto
 let noticia = {
    titulo: 'Los trabajos de extinción frenan el incendio de Castellón y Teruel a las puertas de un parque natural',
    preview: 'El operativo afronta este lunes el día más complicado por las fuertes rachas de viento.',
    contenido: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum' }
</script>


<PreviewComponent noticia={noticia} />


