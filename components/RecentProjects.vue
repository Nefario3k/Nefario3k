<template>
  <section id="projects" class="bg-dark">
    <v-container class="container-fluid rowss">
      <div class="row">
        <div class="col-12">
          <header class="one_piece">Projects</header>
        </div>
        <div
          v-for="item in 9"
          :key="item"
          class="project_item col-6 col-sm-6 col-md-4 col-lg-3"
        >
          <div class="project_item_img"></div>
          <div class="project_item_subtext">
            <p class="header">lorem ipsum dolor</p>
            <p class="subtext">
              Lorem ipsum dolor sit amet condo adipisicing elit. Deleniti natus
              obcaecati alias facere suscipit tempore, atque eum nesciunt
              voluptatibus impedit?
            </p>
            <p class="stacks">Stacks</p>
            <div class="row stacks_field">
              <div class="col-4">Bootstrap</div>
              <div class="col-4">Vuetify</div>
            </div>
          </div>
        </div>
      </div>
    </v-container>
    <v-container class="container-fluid">
      <v-row>
        <div class="col-12">
          <header class="one_piece">Projects</header>
        </div>
        <!-- bizcard  -->
        <div
          class="
            col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6
            project_img_wrapper project_content
          "
        >
          <img src="/images/projects/bizzcard.png" alt="" />
        </div>
        <div
          class="
            col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6
            project_content_wrapper project_content
          "
        >
          <header class="project_title">
            <span class="one_piece">Digital Business card</span>
            <a href="https://bizzcard.net" target="_blank">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <path
                  d="M320 0c-17.7 0-32 14.3-32 32s14.3 32 32 32h82.7L201.4 265.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L448 109.3V192c0 17.7 14.3 32 32 32s32-14.3 32-32V32c0-17.7-14.3-32-32-32H320zM80 32C35.8 32 0 67.8 0 112V432c0 44.2 35.8 80 80 80H400c44.2 0 80-35.8 80-80V320c0-17.7-14.3-32-32-32s-32 14.3-32 32V432c0 8.8-7.2 16-16 16H80c-8.8 0-16-7.2-16-16V112c0-8.8 7.2-16 16-16H192c17.7 0 32-14.3 32-32s-14.3-32-32-32H80z"
                />
              </svg>
            </a>
          </header>
          <p class="project_sub_text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque
            maxime repellendus quos quaerat, commodi ipsam id! Possimus tenetur
            excepturi suscipit ipsam obcaecati vitae tempore tempora praesentium
            laboriosam officia, saepe provident.
          </p>
          <p class="stacks">Stacks</p>
          <div class="row stacks_field">
            <div class="col-4">Bootstrap</div>
            <div class="col-4">Vuetify</div>
          </div>
        </div>
        <v-col cols="12"> <v-divider class="divider"></v-divider></v-col>
        <!-- sena homes  -->
        <div
          class="
            col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6
            project_content_wrapper project_content
          "
        >
          <header class="project_title">
            <span class="one_piece">Real Estate - Sena Homes</span>
            <a
              href="https://nefario3k.github.io/Real-Estate---Sena-Homes/"
              target="_blank"
            >
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <path
                  d="M320 0c-17.7 0-32 14.3-32 32s14.3 32 32 32h82.7L201.4 265.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L448 109.3V192c0 17.7 14.3 32 32 32s32-14.3 32-32V32c0-17.7-14.3-32-32-32H320zM80 32C35.8 32 0 67.8 0 112V432c0 44.2 35.8 80 80 80H400c44.2 0 80-35.8 80-80V320c0-17.7-14.3-32-32-32s-32 14.3-32 32V432c0 8.8-7.2 16-16 16H80c-8.8 0-16-7.2-16-16V112c0-8.8 7.2-16 16-16H192c17.7 0 32-14.3 32-32s-14.3-32-32-32H80z"
                />
              </svg>
            </a>
          </header>
          <p class="project_sub_text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque
            maxime repellendus quos quaerat, commodi ipsam id! Possimus tenetur
            excepturi suscipit ipsam obcaecati vitae tempore tempora praesentium
            laboriosam officia, saepe provident.
          </p>
          <p class="stacks">Stacks</p>
          <div class="row stacks_field">
            <div class="col-4">Bootstrap</div>
            <div class="col-4">Vuetify</div>
          </div>
        </div>
        <div
          class="
            col-12 col-sm-6 col-md-6 col-lg-6 col-xl-6
            project_img_wrapper project_content
          "
        >
          <img src="/images/projects/senahomes.png" alt="" />
        </div>
        <v-col cols="12"> <v-divider class="divider"></v-divider></v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
#projects {
  min-height: 100vh;
  padding-top: 65px;
  color: #fff;
}
.container-fluid {
  &.rowss {
    display: none;
  }
  .project_item {
    min-height: 300px;
    p.header {
      margin-top: 10px;
    }
    .project_item_img {
      width: 100%;
      height: 250px;
      background-color: #d6d8da;
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
    }
  }
  .project_content {
    min-height: 300px;
  }
  .project_img_wrapper {
    width: 100%;
    height: 250px;
    background-color: #d6d8da;
    border-radius: 10px;
    padding: 0;
    overflow-y: auto;
    overflow-x: hidden;
    img {
      width: 100%;
      object-fit: cover;
      object-position: top center;
      height: max-content;
    }
  }
  .project_content_wrapper {
    .project_title {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 20px;
      span {
        width: 85%;
      }
      svg {
        width: 20px;
        height: 100%;
      }
    }
  }
}
::-webkit-scrollbar {
  width: 0px !important;
  height: 0px !important;
}

/* Track */
::-webkit-scrollbar-track {
  box-shadow: none;
  background: transparent;
  /* border-radius: 10px; */
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: transparent;
  /* border-radius: 10px; */
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: transparent;
  transition: all 0.5s linear;
}
</style>