<template>
          <div class="jumbotron">
          <div id="recap">
              <input type="color" name="color" id="color">
            <ul>
              <li>
                Modèle :
                <span id="recap-modele">Salomé</span>
              </li>
              <li>
                L'avant :
                <span id="recap-avant">Aucun</span>
              </li>
              <li>
                L'arrière :
                <span id="recap-arriere">Aucun</span>
              </li>
              <li>
                Options :
                <span id="recap-options">Bride dessus - Bordure - Avant - Arrière</span>
              </li>
              <li>
                Accessoires :
                <span id="recap-accessoire"></span>
              </li>
              <li>
                Brides :
                <span id="recap-bride"></span>
              </li>
              <li>
                Talons :
                <span id="recap-talon">Aiguille 6 cm</span>
              </li>
              <li>
                Semelle :
                <span id="recap-semelle"></span>
              </li>
              <li>
                Doublure :
                <span id="recap-doublure"></span>
              </li>
              <li>
                Pointures :
                <span id="recap-pointure">Choisissez votre pointure</span>
              </li>
            </ul>
          </div>
          <div id="recap-save">
            <div id="tarif">280,00 €</div>
            <div id="acheter">Acheter</div>
            <div id="save">
              <span class="save">Sauvegarder</span>
              <span class="wishlist">Ajouter à ma Wishlist</span>
            </div>
          </div>
        </div>
</template>

<script>
export default {
    name:'Sidebar',

}
</script>

<style>

</style>