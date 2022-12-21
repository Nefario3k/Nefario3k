<template>
  <section id="home">
    <div class="row">
      <aside
        class="
          left
          col-md-6 col-lg-6 col-12
          d-flex
          justify-content-center
          align-items-center
          bg-dark
        "
      >
        <v-avatar class="logo" size="300">
          <img src="/images/frame1.png" alt="NerfSenpai Logo" />
        </v-avatar>
      </aside>
      <aside
        class="
          right
          d-flex
          p-5
          justify-content-center
          flex-column
          col-md-6 col-lg-6 col-12
        "
      >
        <header class="one_piece">Hi' and Welcome</header>
        <h1>I'm <span class="one_piece">Davies Okpeta</span>,</h1>
        <h1>A Software Engineer</h1>
        <div class="header_btn_container">
          <nuxt-link class="header_btn rp" to="/#projects"
            >Recent Project</nuxt-link
          >
          <nuxt-link class="header_btn he" to="/#projects">Hire Me</nuxt-link>
        </div>
      </aside>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
#home {
  /* height: calc(100vh - 82px); */
}
aside.col-12 {
  height: calc(100vh - 58px);
}
aside.right {
}
.header_btn_container {
  display: flex;
  align-items: center;
  gap: 15px;
  width: 100%;
}
.header_btn {
  padding: 10px 0;
  width: 150px;
  text-align: center;
  border-radius: 30px;
  border: 1px solid #222;
  color: #222;
}
.logo {
  /* background-color: #343a40;
  box-shadow: -5px -5px 10px rgba(255, 255, 255, 0.1),
    5px 5px 10px rgba(0, 0, 0, 0.25); */
  background: linear-gradient(145deg, #2f343a, #383e44);
  box-shadow: 5px 5px 10px #2c3136, -5px -5px 10px #3c434a;
}
</style>