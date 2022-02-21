<template>
  <main class="container-fluid">
    <!-- first section -->
    <section
      class="
        baground-lightgray
        row
        justify-content-center
        align-items-center
        pt-3
        pb-3
      "
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
    <section class="row justify-content-center align-items-center pt-3 pb-3">
      <div class="col-12">
        <div class="container height-auto">
          <h4 class="text-color-gray p-3 text-center">WE ARE PROFESSIONAL</h4>
          <h2 class="text-color-lima2 p-2 text-center">
            Full-Service Solution
          </h2>
          <div class="container">
            <div class="row">
              <div class="col-4">
                <div class="card baground-lightgray" style="width: 18rem">
                  <img
                    src="../assets/img/avada-movers-serviceonephoto-final.jpg"
                    class="card-img-top p-3"
                  />
                  <div class="card-body">
                    <h5 class="card-title text-color-demin2 text-center">
                      Two Man Teams
                    </h5>
                    <p class="card-text bg-white text-center p-2">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Rerum, quam quod? Nostrum natus accusamus, aliquid impedit
                      tenetur magnam in ipsa sit, amet ad reprehenderit
                      exercitationem praesentium illo veritatis molestiae
                      provident!
                    </p>
                    <div class="text-center">
                      <button
                        type="button"
                        class="rounded-pill btn-primary p-2 text-center mb-4"
                      >
                        READ MORE
                      </button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-4">
                <div class="card baground-lightgray" style="width: 18rem">
                  <img
                    src="../assets/img/avada-movers-servicetwophoto-final.jpg"
                    class="card-img-top p-3"
                  />
                  <div class="card-body">
                    <h5 class="card-title text-color-demin2 text-center">
                      We Do All The Lifting
                    </h5>
                    <p class="card-text bg-white text-center p-2">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Rerum, quam quod? Nostrum natus accusamus, aliquid impedit
                      tenetur magnam in ipsa sit, amet ad reprehenderit
                      exercitationem praesentium illo veritatis molestiae
                      provident!
                    </p>
                    <div class="text-center">
                      <button
                        type="button"
                        class="rounded-pill btn-primary p-2 text-center mb-4"
                      >
                        READ MORE
                      </button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-4">
                <div class="card baground-lightgray" style="width: 18rem">
                  <img
                    src="../assets/img/avada-movers-servicethreephoto-final.jpg"
                    class="card-img-top p-3"
                  />
                  <div class="card-body">
                    <h5 class="card-title text-color-demin2 text-center">
                      Coast To Coast
                    </h5>
                    <p class="card-text bg-white text-center p-2">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Rerum, quam quod? Nostrum natus accusamus, aliquid impedit
                      tenetur magnam in ipsa sit, amet ad reprehenderit
                      exercitationem praesentium illo veritatis molestiae
                      provident!
                    </p>
                    <div class="text-center">
                      <button
                        type="button"
                        class="rounded-pill btn-primary p-2 text-center mb-4"
                      >
                        READ MORE
                      </button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- third section -->
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

div button {
  font-weight: bold;
}

.height-auto {
  height: auto;
}

.text-color-gray {
  color: $dovegray;
}

.text-color-lima2 {
  color: $lima2;
}

.text-color-demin2 {
  color: $demin2;
}

.baground-lightgray {
  background-color: $lightgray;
}
</style>