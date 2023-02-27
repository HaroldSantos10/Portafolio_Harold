<template>


    <section class="page-section" >

        <div class="container px-4 px-lg-5">
            <div class="row gx-4 gx-lg-5 justify-content-center ">
                <div class="col-lg-8 col-xl-6 text-center">
                            <h2 class="mt-0">Apuntes</h2>
                            <hr class="divider" />
                            <p class="text-muted mb-1">
                            En esta sección pueden encontrarse los apuntes tomados durante el desarrollo de las
                            clases, tanto prácticas como teóricas que fueron impartidas a lo largo de este computo.
                            </p>
                            <br>
                </div>
                
                <carousel :Slides="imagenes" ></carousel>

            </div>
        </div>
    </section>



  </template>
  
<script>

import carousel from '../components/carousel.vue';


export default({
    components:{
        carousel,
        
    },
    data: () => ({
        imagenes: [

            '/src/assets/img/apuntes/img_01.png',
            '/src/assets/img/apuntes/img_02.png',
            '/src/assets/img/apuntes/img_03.png',
            '/src/assets/img/apuntes/img_04.png',
            '/src/assets/img/apuntes/img_05.png',
            '/src/assets/img/apuntes/img_113.png',
            '/src/assets/img/apuntes/img_123.png',
            '/src/assets/img/apuntes/img_06.png',
            '/src/assets/img/apuntes/img_07.png',
            '/src/assets/img/apuntes/img_08.png',
            '/src/assets/img/apuntes/img_09.png',
            '/src/assets/img/apuntes/img_10.png',

            
        ]
    })
});


</script>
  