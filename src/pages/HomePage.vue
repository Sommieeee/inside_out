<template>
  <div>
    <q-layout container style="height: 100vh">
      <q-header class="toolbar">
        <q-toolbar>
          <q-btn flat round dense icon="menu" class="q-mr-sm" />

          <center>
            <q-toolbar-title
              ><img class="insideout" src="~assets/images/insideout-logo.png" />
            </q-toolbar-title>
          </center>
          <q-btn flat round dense icon="search" />
          <q-btn flat dense icon="favorite_border" />
          <q-btn flat dense icon="shopping_bag" />
        </q-toolbar>
      </q-header>
      <q-page-container>
        <center>
          <img class="percent" src="~assets/images/percent.jpeg" />
        </center>
        <div class="def">
          <q-card class="my-card">
            <img src="~assets/images/top1.png" />
            <q-card-section>
              <div class="name">Off-Shoulder Black Crop Top</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/top2.png" />
            <q-card-section>
              <div class="name">Sleeveless Top</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/top3.png" />
            <q-card-section>
              <div class="name">Adidas Crop Top</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/top4.png" />
            <q-card-section>
              <div class="name">Blue Print Top</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/bottom5.png" />
            <q-card-section>
              <div class="name">Black Shorts</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/bottom2.png" />
            <q-card-section>
              <div class="name">Green Short</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/bottom3.png" />
            <q-card-section>
              <div class="name">Blue Jeans Shorts</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/bottom4.png" />
            <q-card-section>
              <div class="name">Dungaree</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/dress1.png" />
            <q-card-section>
              <div class="name">Red Print Dress</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/dress2.png" />
            <q-card-section>
              <div class="name">Blue Dress</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/dress3.png" />
            <q-card-section>
              <div class="name">Bodycon Dress</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
          <q-card class="my-card">
            <img src="~assets/images/dress4.png" />
            <q-card-section>
              <div class="name">White Lace Dress</div>
              <div class="price">$7.99</div>
            </q-card-section>
            <q-card-actions>
              <q-btn flat dense icon="favorite_border" />
              <q-btn flat dense icon="shopping_cart" />
            </q-card-actions>
          </q-card>
        </div>
      </q-page-container>
    </q-layout>
  </div>
</template>
<style lang ="scss">
.toolbar {
  background-color: whitesmoke;
  color: black;
}
.insideout {
  width: 15%;
}
.def {
  display: flex;
  flex-wrap: wrap;
  margin-top: 10px;
  justify-content: center;
  grid-gap: 20px;
}
.my-card {
  width: 20%;
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 20px;
  margin-bottom: 30px;
}
.name {
  font-size: 16;
  color: grey;
}
.price {
  font-size: 18;
  color: black;
  font-weight: 600;
}
.percent {
  height: 250px;
}
.def img {
  aspect-ratio: 3/3;
  object-fit: contain;
}
</style>
