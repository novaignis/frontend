<template>
  <section id="page-404" class="bg--white-300 division">
    <div class="container">
      <div class="row justify-content-center">
        <!-- 404 PAGE TEXT -->
        <div class="col-md-9 col-lg-8">
          <div class="page-404-txt text-center">
            <!-- Image -->
            <div class="rel page-404-img">
              <img
                class="img-fluid"
                src="/assets/images/error-404.png"
                alt="error-404-img"
              />
            </div>

            <!-- Text -->
            <h2 class="s-56 w-700 color--dark">Página No Encontrada</h2>
            <h6 class="s-22 color--grey">
              Oops! Parece que la página que intentas visitar ha sido movida, renombrada o pueda que no exista.
            </h6>

            <!-- Button -->
            <a href="/" class="btn btn--theme hover--theme"
            @click="handleError" >Volver a Nova Ignis</a
            >
          </div>
        </div>
        <!-- END 404 PAGE TEXT -->
      </div>
      <!-- End row -->
    </div>
    <!-- End container -->
  </section>
  <hr class="divider divider-light" />

</template>


<script setup lang="ts">
const props = defineProps({
  error: Object
})
useHead({
        bodyAttrs: {
            class: "navbar-light scheme-violet"
        },
    })
const handleError = () => clearError({ redirect: '/' })
</script>
