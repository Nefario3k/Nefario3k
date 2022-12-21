<template>
  <section id="about">
    <v-container class="container-fluid"
      ><div class="about_wrapper d-flex align-items-center p-5">
        <div class="row">
          <div class="left col-12">
            <header class="one_piece about_title">About me</header>
            <p class="about_me_context text-justify">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Magnam
              sapiente harum adipisci illo ad sit ipsa! Harum suscipit
              provident, temporibus error vero incidunt! Cum fugiat modi unde
              fuga iste adipisci non ut, neque ab beatae necessitatibus fugit
              numquam nulla cumque amet quae? Reiciendis in beatae fugiat!
              Repellat, dolor temporibus animi dolore nisi sapiente quis tempora
              labore ipsam minima accusamus commodi quod fugit neque!
              Perspiciatis, minus soluta ratione natus velit distinctio quos,
              nobis fugit quibusdam aspernatur itaque asperiores cum magni
              pariatur. Qui facilis nobis, sit voluptatum ratione mollitia in!
              Eum dolorum velit expedita, mollitia quae itaque alias porro dolor
              nulla corporis.
            </p>
          </div>
        </div>
      </div></v-container
    >
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
#about {
  height: 100vh;
  color: #222;
  margin-top: 12px;
  padding-top: 15px;
}

.about_wrapper {
  background: transparent;
  width: 80%;
  margin: 0 auto;
  height: calc(100vh - 80px);
  color: #222;
}
.about_me_context {
  font-style: italic;
}
</style>