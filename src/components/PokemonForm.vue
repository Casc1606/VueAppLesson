<script setup lang="ts">
</script>

<template>
    <div class="row">
        <div class="col">
            <form>
                <div class="mb-3">
                    <div id="emailHelp" class="form-text">
                        <h1>Adivina el pokemon!</h1>
                    </div>
                    <label for="exampleInput" class="form-label">Pokemon</label>
                    <input type="text" class="form-control" id="pokemonInput" aria-describedby="emailHelp">
                </div>
                <div class="mb-3">
                    <label for="exampleInput1" class="form-label">Url</label>
                    <input type="text" class="form-control" id="urlInput">
                </div>
                <button type="button" class="btn btn-primary" id="bringThePokemon_btn">Bring the Pokemon</button>
                <button type="button" class="btn btn-primary" id="send_btn">Send</button>
                <button type="button" class="btn btn-primary" id="bringmyapi_btn">Trae mi API</button>
            </form>
        </div>
        <div class="col">
            <div class="accordion" id="accordionPanelsStayOpenExample">
                <div class="accordion-item">
                    <h2 class="accordion-header" id="panelsStayOpen-headingOne">
                        <button class="accordion-button" type="button" data-bs-toggle="collapse"
                            data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true"
                            aria-controls="panelsStayOpen-collapseOne">
                            Imagen Pokemon Frontal
                        </button>
                    </h2>
                    <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show"
                        aria-labelledby="panelsStayOpen-headingOne">
                        <div class="accordion-body">
                            <div class="container">
                                <div class="card" style="width: 18rem;">
                                    <img class="card-img-top" id="imgPokemonFrontal">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="accordion-item">
                    <h2 class="accordion-header" id="panelsStayOpen-headingThree">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                            data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false"
                            aria-controls="panelsStayOpen-collapseThree">
                            Imagen Pokemon Trasera
                        </button>
                    </h2>
                    <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse"
                        aria-labelledby="panelsStayOpen-headingThree">
                        <div class="accordion-body">
                            <div class="container">
                                <div class="card" style="width: 18rem;">
                                    <img class="card-img-top" id="imgPokemonTrasera">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>