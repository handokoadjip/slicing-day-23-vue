<template>
  <header class="mb-5">
    <nav class="navbar navbar-light p-3 border-bottom">
      <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <router-link class="navbar-brand text-center d-none d-lg-block text-uppercase mp-0 fw-bolder fs-5" to="#">
          adam widmanski
        </router-link>

        <div class="navbar-brand d-flex justify-content-center align-items-center">
          <router-link class="text-decoration-none" to="#"><i class="fab fa-twitter"></i></router-link>
        </div>

        <div class="collapse navbar-collapse mt-3" id="navbarNav">
          <ul class="navbar-nav text-uppercase">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">home</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

