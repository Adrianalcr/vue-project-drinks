<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import MenuIcon from './icons/IconMenu.vue'
import CoffeeIcon from './icons/IconCoffee.vue'
import DrinksIcon from './icons/IconDrinks.vue'
import WineIcon from './icons/IconWine.vue'
import BeerIcon from './icons/IconBeer.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <MenuIcon />
    </template>
    
    <template #heading>
      <img alt="Menu" class="menu" src="@/assets/img/menu.png" width="100"  height="100"/>
    </template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CoffeeIcon />
    </template>

    <dl>
      <dt>Cofee</dt>
      <dd class="price">$ 0,99</dd>
      <dd class="ingredients">With Milk</dd>
    </dl>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DrinksIcon />
    </template>

    <dl>
      <dt>Fruit juice</dt>
      <dd class="price">$ 3,00</dd>
      <dd class="ingredients">With Milk</dd>
    </dl>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <WineIcon />
    </template>

    <dl>
      <dt>Wine</dt>
      <dd class="price">$ 5,00</dd>
      <dd class="ingredients">Red and White</dd>
    </dl>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <BeerIcon />
    </template>

    <dl>
      <dt>Beers</dt>
      <dd class="price">$ 4,00</dd>
      <dd class="ingredients">Ice</dd>
    </dl>
  </WelcomeItem>
</template>


<style>
.menu img{
  max-width: 100% !important;
  height: auto;
  object-fit: cover;
  align-items: center;
}

dl {
  background: transparent;
  border: 1px solid var(--vt-c-divider-dark-2);
  border-radius: 0 15px;
  padding: 2px 15px;
  margin: 0 0 1em;
  overflow: auto;
  width: 100%;
}

dt,
dd.price {
  font-size: 1.8em;
  font-weight: bold
}

dt {
  color: #f7ce00;
  float: left;
  padding-right: 3px
}

dd {
  margin: 0
}

dd.price {
  color: #aaa;
  float: right;
  padding-left: 3px
}

dd.ingredients {
  color: #555;
  font: italic 1.2em Georgia, Times, sans-serif;
  float: left;
  padding: 3px 0;
  width: 100%
}

#menu h1{
  color: #f7ce00;
  font: italic 1.2em Georgia, Times, sans-serif;
  float: left;
  padding: 3px 0;
  width: 100%
}
</style>