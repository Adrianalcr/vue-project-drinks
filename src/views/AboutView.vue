<template>
  <div class="about">
    <h1>This is an about page</h1>
    <img src="@/assets/img/icone.png" width="200" height="200"/>
    <div class="text-p">
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
        Officia sunt eos placeat doloribus! Tenetur consequatur ab 
        temporibus quaerat molestias beatae iste amet. 
        Soluta minima quis praesentium, amet quaerat dolore repellat!
      </p>
      
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
        Officia sunt eos placeat doloribus! Tenetur consequatur ab 
        temporibus quaerat molestias beatae iste amet. 
        Soluta minima quis praesentium, amet quaerat dolore repellat!
      </p>
    </div>
  </div>
</template>

<style>
.about h1{
  color: #555;
  font: italic 3em Georgia, Times, sans-serif;
  text-align: center;
  padding: 3px 0;
  width: 100%;
  margin-top: 30px;
}

.about .text-p{
  padding: 55px;
}

@media (min-width: 1024px) {
  .about {
    width: 100%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
