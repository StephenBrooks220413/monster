<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
      <!-- Container wrapper -->
      <div class="container-fluid">
        <!-- Navbar brand -->
        <a class="navbar-brand" href="#">MonsterIT</a>

        <!-- Toggle button -->
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>

        <!-- Collapsible wrapper -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <!-- Left links -->
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about">About</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/services">
                Pricing
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/catalog">
                Catalog
              </router-link>
            </li>
            <!-- Navbar dropdown -->
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-mdb-toggle="dropdown"
                aria-expanded="false"
              >
                Dropdown
              </a>
              <!-- Dropdown menu -->
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <a
                    href="https://github.com/StephenBrooks220413"
                    class="dropdown-item"
                    target="_blank"
                  >
                    Github
                  </a>
                </li>
                <li>
                  <a
                    href="https://www.linkedin.com/in/stephen-brooks-897a1110a/"
                    class="dropdown-item"
                    target="_blank"
                  >
                    LinkedIn
                  </a>
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a
                    href="https://www.youracclaim.com/users/stephenallenbrooks"
                    class="dropdown-item"
                    target="_blank"
                  >
                    Acclaim
                  </a>
                </li>
              </ul>
            </li>
          </ul>
          <!-- Left links -->

          <!-- Search form -->
          <!--<div class="d-flex w-auto">
            <a href="#" target="_blank" >
              Accounts
            </a>
          </div> -->
        </div>
        <!-- Collapsible wrapper -->
      </div>
      <!-- Container wrapper -->
    </nav>
  </div>
  <br />
  <br />
  <router-view />
</template>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
