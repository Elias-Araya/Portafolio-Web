<template>
  <!-- Portfolio Grid-->
        <section class="page-section bg-light" id="portfolio">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">Proyectos</h2>
                    <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
                </div>
                <div class="card-deck p-3" style="">
                    <div class="card" style="width: 18rem;">
                        <div class="work-img">
                        <img class="card-img-top" src="../assets/img/digimon.jpg" alt="o,">
                        </div>
                        <div class="card-body">
                            <h5 class="card-title">Digimon Api</h5>
                            <p class="card-text">Pagina que lista todos los digimones, ordenados alfabeticamente y pudiendo ser filtrados por su 'level' utlizando la Api de Digimon</p>
                        </div>
                        <div class="card-footer text-muted">
                            <a class="btn btn-dark btn-social mx-2" href="https://github.com/Elias-Araya/DigimonApi#readme" target="_blank"><i class="fab fa-github"></i></a>
                            <a class="btn btn-dark btn-social mx-2" href="https://digimon-filter.netlify.app" target="_blank"><i class="fab fa-chrome"></i></a>

                        </div>
                    </div>
                    <div class="card" style="width: 18rem;">
                        <img class="card-img-top" src="../assets/img/firebasebueno.png"  alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Tareas Fire Base</h5>
                            <p class="card-text">Sitio con sistema de login, que permite a los usuarios registrados añadir/editar/eliminar tareas. <br>
                                                 Vue es utlizado como el front y firebase como back.
                            </p>
                        </div>
                        <div class="card-footer text-muted">
                            <a class="btn btn-dark btn-social mx-2" href="https://github.com/Elias-Araya/Tareas-Firebase" target="_blank"><i class="fab fa-github"></i></a>
                            <a class="btn btn-dark btn-social mx-2" href="https://tareas-firebase.netlify.app" target="_blank"><i class="fab fa-chrome"></i></a>

                        </div>
                    </div>
                    <div class="card" style="width: 18rem;">
                        <img class="card-img-top" src="../assets/img/portafolio.png" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Portafolio</h5>
                            <p class="card-text">Pagina web creada a partir de un template de Bootstrap</p>
                           
                        </div>
                        <div class="card-footer text-muted">
                            <a class="btn btn-dark btn-social mx-2" href="#!"><i class="fab fa-github"></i></a>
                            <a class="btn btn-dark btn-social mx-2" href="https://portafolio-boots.netlify.app"><i class="fab fa-chrome"></i></a>

                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.work-img {
    display: block;
    overflow: hidden;
}

.card-img-top {
    height: 300px;
    widows: 350px;
}
</style>

