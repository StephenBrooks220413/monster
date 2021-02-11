<template>
  <div class="home">
    <div class="jumbotron">
      <img src="../assets/logo.png"
         alt="logo"
         width="330px"
      />
    </div>
    <div class="container text-center">
      <hr />
      <HelloWorld msg="Welcome to Your Vue.js + TypeScript Developer" />
      <br /><br /><br /><br />
      <h1>Projects I created</h1>
      <h5>
        These were paid for by previous clients and maintained by their own
        developer
      </h5>
      <!-- Carousel wrapper -->
      <div
        id="carouselBasicExample"
        class="carousel slide carousel-fade"
        data-mdb-ride="carousel"
      >
        <!-- Indicators -->
        <ol class="carousel-indicators">
          <li
            data-mdb-target="#carouselBasicExample"
            data-mdb-slide-to="0"
            class="active"
          ></li>
          <li
            data-mdb-target="#carouselBasicExample"
            data-mdb-slide-to="1"
          ></li>
          <li
            data-mdb-target="#carouselBasicExample"
            data-mdb-slide-to="2"
          ></li>
        </ol>

        <!-- Inner -->
        <div class="carousel-inner">
          <!-- Single item -->
          <div class="carousel-item active">
            <img
              src="https://images.unsplash.com/photo-1598887142487-3c854d51eabb?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
              class="d-block w-100"
              alt="..."
            />
            <div class="carousel-caption d-none d-md-block">
              <h1>
                <a
                  href="https://barber-cuts.netlify.app/"
                  class="text-white"
                  target="_blank"
                >
                  Barber Shop
                </a>
              </h1>
              <p class="text-white">
                Application Built With jQuery, Bootstrap, scss, css and HTML
              </p>
            </div>
          </div>

          <!-- Single item -->
          <div class="carousel-item">
            <img
              src="https://images.unsplash.com/photo-1563453392212-326f5e854473?ixid=MXwxMjA3fDB8MHxzZWFyY2h8Mnx8Y2xlYW5pbmd8ZW58MHx8MHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=60"
              class="d-block w-100"
              alt="..."
            />
            <div class="carousel-caption d-none d-md-block">
              <h1>
                <a
                  href="https://kees-cleaning-service.netlify.app/"
                  target="_balnk"
                  class="text-dark"
                >
                  Kee's Cleaners
                </a>
              </h1>
              <p class="text-dark">
                For the office and home cleaning solutions.
              </p>
            </div>
          </div>

          <!-- Single item -->
          <div class="carousel-item">
            <img
              src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MXx8aW5zdXJhbmNlfGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=60"
              class="d-block w-100"
              alt="..."
            />
            <div class="carousel-caption d-none d-md-block">
              <h1>
                <a
                  href="https://www.brookslifeagency.net/"
                  class="text-dark"
                  target="_blank"
                >
                  Insurance Advisor
                </a>
              </h1>
              <p class="text-dark">For all of your insurance solutions.</p>
            </div>
          </div>
        </div>
        <!-- Inner -->

        <!-- Controls -->
        <a
          class="carousel-control-prev"
          href="#carouselBasicExample"
          role="button"
          data-mdb-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselBasicExample"
          role="button"
          data-mdb-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </a>
      </div>
      <!-- Carousel wrapper -->
      <br /><br /><br />
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

