<template>
  <main class="container-fluid">
    <!-- first section -->
    <section
      class="baground-mercury row justify-content-center align-items-center"
    >
      <div class="col-12">
        <div class="container height-auto">
          <h4 class="text-color-gray p-3 text-center">HEADACHE FREE</h4>
          <h2 class="text-color-lima2 p-2 text-center">
            Award Winning Moving Company
          </h2>
          <p class="p-2 text-center">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsa odit
            deleniti cumque, aperiam impedit, earum fugiat praesentium hic nisi
            autem officiis illum optio veritatis exercitationem distinctio?
            Doloremque blanditiis id possimus.
          </p>
          <div class="text-center">
            <button
              type="button"
              class="rounded-pill btn-primary p-3 text-center mb-4"
            >
              READ OUR TESTIMONIALS
            </button>
          </div>
        </div>
      </div>
    </section>
    <!-- second section -->
    <section>Qui Main</section>
    <section>Qui Main</section>
    <section>Qui Main</section>
    <section>Qui Main</section>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

.height-auto {
  height: auto;
}

.text-color-gray {
  color: $dovegray;
}

.text-color-lima2 {
  color: $lima2;
}

.baground-mercury {
  background-color: $mercury;
}
</style>