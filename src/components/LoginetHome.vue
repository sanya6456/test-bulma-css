<template>
  <nav class="navbar is-fixed-top is-light" role="navigation" aria-label="dropdown navigation">
    <div class="navbar-brand ml-2">
      <a href="#" class="navbar-item">
        <img src="../assets/gallery/loginet_logo_nav_color.svg" alt="LogiNet" />
      </a>
      <a href="#" class="navbar-burger" data-target="navMenu"  id="navBurger">
        <span></span>
        <span></span>
        <span></span>
      </a>
    </div>
    <div class="navbar-menu" id="navMenu">
      <div class="navbar-start">
        <a href="#" class="navbar-item">Főoldal</a>
        <a href="#" class="navbar-item">Hírek</a>

        <div class="navbar-item has-dropdown is-hoverable">
          <a href="#" class="navbar-link">Egyéb</a>
          <div class="navbar-dropdown">
            <a href="#" class="navbar-item">Rólunk</a>
            <a href="#" class="navbar-item">Karrier</a>
            <a href="#" class="navbar-item">Kapcsolat</a>
            <a href="#" class="navbar-item">Hiba bejelentés</a>
          </div>
        </div>
      </div>
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <div class="button">Regisztráció</div>
            <div class="button orange-btn">Bejelentkezés</div>
          </div>
        </div>
      </div>
    </div>
  </nav>


  <!-- Landing Page -->
  <section
    class="hero landing-page has-text-centered is-flex-column is-justify-content-center is-align-items-center"
  >
    <div>
      <div class="has-text-white is-size-2 is-size-3-mobile has-text-weight-semibold">
        HOGYAN HOZD KI A LEGTÖBBET AZ E-KERESKEDELEMBŐL?
      </div>
      <div class="has-text-grey-lighter is-size-4 is-size-5-mobile  mt-1">
        Tudd meg E-commerce sikerkönyvünkből!
      </div>
      <div class="button orange-btn is-size-5 is-size-6-mobile mt-5" @click="downloadEbook">Letöltöm az ebookot!</div>
    </div>

    <!-- popup -->
    <div class="modal" id="popup">
      <div class="modal-background"></div>
      <div class="modal-content">
        <div class="box has-background-danger has-text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae error, voluptate nulla doloremque eaque sit possimus impedit aspernatur blanditiis quos sapiente, laborum sequi suscipit corrupti aliquam est voluptates nisi doloribus dolorum eos eligendi reiciendis enim nobis! Officia quibusdam tenetur quos blanditiis id ipsum eos nesciunt tempora neque vel in itaque ipsa, sequi enim dolore possimus ea earum, eligendi laborum eaque cumque est iure molestiae commodi. Sunt debitis dignissimos, eius ipsum delectus hic autem cupiditate magni labore, quaerat explicabo aspernatur sequi aliquid neque ducimus tempore assumenda distinctio doloremque reiciendis provident magnam mollitia fuga illo.</div>
      </div>
      <button class="modal-close is-large" aria-label="close" @click="closePopup"></button>
    </div>

  </section>
  <!-- Digital services -->
  <section class="hero">
    <div class="hero-body">
      <div class="container">
        <!-- Services title -->
        <div class="is-size-2 has-text-weight-semibold">
          Digitális fejlesztési szolgáltatások
        </div>
        <div class="is-size-4 mb-5">
          Olyan rendszereket tervezünk, fejlesztünk, integrálunk, amelyek
          kiemelkedő felhasnálói élményt nyújtanak, versenyelőnyt biztosítanak
          valamennyi digitális csatornán.
        </div>
        <!-- column cards -->
        <div class="columns is-multiline">
          <!-- 1. -->
          <div class="column is-6-tablet is-3-fullhd">
            <div class="box p-0">
              <div class="hero">
                <img src="../assets/gallery/TILE_4NmwlW.jpg" alt="" />
              </div>
              <div class="block p-5">
                <div class="has-text-weight-semibold mb-3 is-size-5">
                  E-commerce fejlesztés
                </div>
                <div class="">
                  Professzionális e-kereskedelmi rendszerek felépítése komplex
                  szolgáltatással: stratégia, tanácsadás, tervezés, fejlesztés,
                  support.
                </div>
                <div class="buttons is-flex is-justify-content-flex-end mt-4">
                  <div class="button orange-btn">Tovább</div>
                </div>
              </div>
            </div>
          </div>
          <!-- 2. -->
          <div class="column is-6-tablet is-3-fullhd">
            <div class="box p-0">
              <div class="hero">
                <img src="../assets/gallery/TILE_Af275g.jpg" alt="" />
              </div>
              <div class="block p-5">
                <div class="has-text-weight-semibold mb-3 is-size-5">
                  Webes szoftverfejlesztés
                </div>
                <div class="">
                  A hatékonyabb vállalati működést segítő egyedi fejlesztések
                  közép- és nagyvállalatok, startupok igényeire hangoltan.
                </div>
                <div class="buttons is-flex is-justify-content-flex-end mt-4">
                  <div class="button orange-btn">Tovább</div>
                </div>
              </div>
            </div>
          </div>
          <!-- 3. -->
          <div class="column is-6-tablet is-3-fullhd">
            <div class="box p-0">
              <div class="hero">
                <img src="../assets/gallery/TILE_bmq8Q1.jpg" alt="" />
              </div>
              <div class="block p-5">
                <div class="has-text-weight-semibold mb-3 is-size-5">
                  Mobil applikáció fejlesztés
                </div>
                <div class="">
                  A mobil célcsoport eléréséhez ideális megoldások tervezése és
                  fejlesztése natív Android, iOS megoldásokkal, saját termékkel.
                </div>
                <div class="buttons is-flex is-justify-content-flex-end mt-4">
                  <div class="button orange-btn">Tovább</div>
                </div>
              </div>
            </div>
          </div>
          <!-- 4. -->
          <div class="column is-6-tablet is-3-fullhd">
            <div class="box p-0">
              <div class="hero">
                <img src="../assets/gallery/TILE_LZViy7.jpg" alt="" />
              </div>
              <div class="block p-5">
                <div class="has-text-weight-semibold mb-3 is-size-5">
                  Nagyvállalati szoftverfejlesztés
                </div>
                <div class="">
                  IT fejlesztési projektek a nagyvállalatok komplex elvárásainak
                  megfelelve.
                </div>
                <div class="buttons is-flex is-justify-content-flex-end mt-4">
                  <div class="button orange-btn">Tovább</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <!-- Products section -->
  <section class="hero">
    <div class="hero-body">
      <div class="container">
        <!-- Product title section -->
          <div class="is-size-2 has-text-weight-semibold">
            Termékeink
          </div>
          <div class="is-size-4 mb-5">
            Digitális megoldásaink az üzletmenet hatékonyabbá tételéhez.
          </div>
          <!-- Products tiles -->
          <div class="tile is-ancestor is-size-4-touch is-size-3-tablet has-text-weight-semibold">
            <!--left-->
            <div class="tile is-vertical is-6">
              <div class="tile">
                <div class="tile is-parent is-vertical">
                  <div class="tile is-child box box orange-btn">Webshop ökoszisztéma</div>
                  <div class="tile is-child box box orange-btn">Mcomapp Mobilshop</div>
                </div>
              </div>
            </div>
            <!--right-->
            <div class="tile is-vertical is-6">
                <div class="tile is-parent">
                  <div class="tile is-child box orange-btn">Salesman Tracker</div>
                </div>
              <div class="tile is-horizontal">
                <div class="tile is-parent">
                  <div class="tile is-child box orange-btn">Archivátor</div>
                </div>
                <div class="tile is-parent">
                  <div class="tile is-parent is-vertical p-0">
                  <div class="tile is-child box box orange-btn">Webshop ökoszisztéma</div>
                  <div class="tile is-child box box orange-btn">Mcomapp Mobilshop</div>
                </div>
                </div>
              </div>
            </div>
          </div>
      </div>
    </div>
  </section>


  <!-- Contact section -->
  <section class="hero">
    <div class="hero-body">
      <div class="container">
          <!-- Contact title section -->
          <div class="is-size-2 has-text-weight-semibold">
            Lépjen velünk kapcsolatba!
          </div>
          <div class="is-size-4 mb-5">
            Felkeltettük érdeklődését? Küldje el ajánlatkérését, vegye fel velünk a kapcsolatot! Az üzenet elküldése után 72 órán belül jelentkezni fogunk.
          </div>
          <!-- Form -->
          <!-- Name -->
          <div class="field">
            <label class="label">Név</label>
            <div class="control">
              <input class="input" type="text" placeholder="Név" v-model="state.name">
            </div>
          </div>
          <!-- Email -->
          <div class="field">
            <label class="label">Email cím</label>
            <div class="control">
              <input class="input" type="email" placeholder="Email cím" v-model="state.email">
            </div>
          </div>
          <!-- Subject -->
          <div class="field">
            <label class="label">Tárgy</label>
            <div class="select">
              <select v-model="state.subject">
                <option value="" disabled selected>Válasszon egy lehetőséget</option>
                <option value="Válaszd ezt!">Válaszd ezt!</option>
                <option value="Vagy ezt!">Vagy ezt!</option>
              </select>
            </div>
          </div>
          <!-- Message -->
          <div class="field is-vertical">
            <div class="field is-normal">
              <label class="label">Üzenet</label>
            </div>
            <div class="field-body">
              <div class="field">
                <div class="control">
                  <textarea class="textarea" placeholder="Ide írhatod az üzenetedet" v-model="state.message"></textarea>
                </div>
              </div>
            </div>
          </div>
          <!-- Checkbox -->
          <div class="field">
            <div class="control">
              <label class="checkbox">
                <input type="checkbox" v-model="state.checkbox">
                Elfogadom az <a href="#">Adatvédelmi nyilatkozatban</a> foglaltakat.
              </label>
            </div>
          </div>
          <!-- Button group -->
          <div class="field is-grouped">
            <p class="control">
              <a class="button orange-btn">
                Küldés
              </a>
            </p>
            <p class="control">
              <a class="button is-link" @click="clearContactForm">
                Mégse
              </a>
            </p>
          </div>
          <!-- All rights reserved -->
          <p class="has-text-centered is-size-5 my-6 py-6"><strong>LogiNet Systems Kft.</strong> &copy; 2020. Digital development services since 2008.</p>

      </div>
    </div>
  </section>
</template>


<script>
import {reactive} from 'vue'

export default {
  name: "LoginetHome",
  setup(){

    // v-model info stores here
    const state=reactive({
      name:'',
      email:'',
      subject:'',
      message:'',
      checkbox:false
    })

    // Clear contact form on click 'Mégse'
    function clearContactForm(){
      state.name='',
      state.email='',
      state.subject='',
      state.message='',
      state.checkbox=false
    }

    //This is bulma's basic hamburger opener code!
    document.addEventListener('DOMContentLoaded', () => {
      const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);
      if ($navbarBurgers.length > 0) {
        $navbarBurgers.forEach( el => {
          el.addEventListener('click', () => {
            const target = el.dataset.target;
            const $target = document.getElementById(target);
            el.classList.toggle('is-active');
            $target.classList.toggle('is-active');
          });
        });
      }
    });

    //popup active
    function downloadEbook(){
      var popup=document.getElementById('popup');
      popup.classList.add('is-active');
    }

    //popup disabled
    function closePopup(){
      var popup=document.getElementById('popup');
      popup.classList.remove('is-active')
    }
    
    return{
      state,
      clearContactForm,
      downloadEbook,
      closePopup
    }

  }

};
</script>


<style scoped lang="scss">
$orange: #e5692c;
/* Primary button */
.orange-btn {
  background-color: $orange;
  color: white;
  border: none;
}
// landing page background
.landing-page {
  background-image: url(../assets/gallery/MAINPAGE_8eMt9a.jpg);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 75vh;
}


</style>
