<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>城堡</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-12">
        <div class="spw">
          <em
            >這篇文章是將有關於城堡的裝甲。而關於城堡請參見<nuxt-link
              to="/building/Castle"
              >城堡</nuxt-link
            ></em
          >
        </div>
      </div>
      <div class="col-md-12">
        <div class="n1">
          <p>
            城堡裝甲是一個防禦裝甲類別，所有在這個系列的建築都會被對該裝甲的有攻擊加成的兵種或科技有額外的傷害。
          </p>
        </div>
        <h3>城堡</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <img width="25px" src="~assets/Castleicon.png" alt="" /><nuxt-link
                to="/building/Castle"
                >城堡</nuxt-link
              >
            </li>
          </ul>
        </div>
        <h3>剋城堡的單位與建築</h3>
        <div class="hrn1"></div>
        <div class="n1">
          以下單位擁有對城堡的額外傷害，按照傷殺力排列。
          <div class="n1">
            <div style="margin:12px 0px;"><strong>+100攻擊</strong></div>
            <ul>
              <li>
                <img class="gg" src="~assets/PetardIcon.jpg" alt="" /><nuxt-link
                  to="/units/Petard"
                  >爆炸桶</nuxt-link
                >
              </li>
            </ul>
            <div style="margin:12px 0px;"><strong>+10攻擊</strong></div>
            <ul>
              <li>
                <img class="gg" src="~assets/TarkanIcon.jpg" alt="" /><nuxt-link
                  to="/units/Tarkan"
                  >韃靼騎兵</nuxt-link
                >→
                <img class="gg" src="~assets/TarkanIcon.jpg" alt="" /><nuxt-link
                  to="/units/Tarkan"
                  >精銳韃靼騎兵</nuxt-link
                >(<nuxt-link to="/civs/Huns">匈奴</nuxt-link>限定)
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'alllarmor',
  components: {}
}
</script>
<style></style>
