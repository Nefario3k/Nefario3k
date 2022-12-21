<template>
  <section id="skillset" class="bg-dark">
    <v-container class="container-fluid">
      <div class="row">
        <!-- css frame works  -->
        <div class="col-12">
          <header class="one_piece">CSS Frameworks</header>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img bootstrap"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">Bootstrap</p>
          </div>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img vuetify"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">Vuetify</p>
          </div>
        </div>
        <!-- front-end frame works  -->
        <div class="col-12">
          <header class="one_piece">Front-end Frameworks</header>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img express"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">Express</p>
          </div>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img vue"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">Vue</p>
          </div>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img nuxt"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">Nuxt</p>
          </div>
        </div>
        <!-- back-end   -->
        <div class="col-12">
          <header class="one_piece">Back-end</header>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img sql"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">SQL</p>
          </div>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img mdb"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">MongoDb</p>
          </div>
        </div>
        <div class="project_item col-6 col-sm-6 col-md-4 col-lg-3">
          <div class="project_item_img laravel"></div>
          <div class="project_item_subtext">
            <p class="stacks text-center">Laravel</p>
          </div>
        </div>
      </div>
    </v-container>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
#skillset {
  min-height: 100vh;
  padding-top: 65px;
  color: #fff;
}
.project_item {
  min-height: 300px;
}
.stacks {
  margin-top: 10px;
}
.project_item_img {
  width: 100%;
  height: 250px;
  background: rgba(214, 216, 218, 0.65);
  box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border-radius: 10px;
  border: 1px solid rgba(255, 255, 255, 0.18);
  background-repeat: no-repeat;
  /* background-color: rgba(214, 216, 218, 0.2);
  border-radius: 8px;
  border: 1px solid rgba(214, 216, 218, 0.2);
  box-shadow: 5px 5px 30px rgba(0, 0, 0, 0.1);
  transition: all 0.5s ease-in-out;
  backdrop-filter: blur(20px); */
  background-image: url('/images/skills/bootstrap.png');
  background-size: 80%;
  background-position: top 50% center;
}
.project_item_img.bootstrap {
  background-image: url('/images/skills/bootstrap.png');
  background-size: 100%;
}
.project_item_img.vuetify {
  background-image: url('/images/skills/vuetify.svg');
}
.project_item_img.express {
  background-image: url('/images/skills/express.png');
}
.project_item_img.vue {
  background-image: url('/images/skills/vue.png');
}
.project_item_img.nuxt {
  background-image: url('/images/skills/nuxt.svg');
}
.project_item_img.sql {
  background-image: url('/images/skills/sql.svg');
}
.project_item_img.mdb {
  background-image: url('/images/skills/MongoDB.svg');
}
.project_item_img.laravel {
  background-image: url('/images/skills/Laravel.svg');
}
</style>