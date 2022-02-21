<template>
  <header class="container-fluid">
    <div class="row">
      <div class="col-12 baground-lima2">
        <div class="container">
          <div class="row align-items-center justify-content-between">
            <div class="col-3">Call us for a Free Quote: 1.800.555.6789</div>
            <div class="col-3">
              <nav class="navbar d-flex">
                <form class="container-fluid justify-content-end">
                  <ul class="d-flex">
                    <li>
                      <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                    </li>
                    <li>
                      <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    </li>
                    <li>
                      <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    </li>
                    <li>
                      <a href="#"><i class="fa-brands fa-youtube"></i></a>
                    </li>
                  </ul>
                </form>
              </nav>
            </div>
          </div>
        </div>
      </div>
      <div class="col-12">
        <div class="container p-3">
          <div class="row align-items-center justify-content-between">
            <div class="col-3">
              <img src="../assets/img/avada-movers-logo.png" />
            </div>
            <div class="col-7">
              <nav class="navbar">
                <form class="container-fluid justify-content-start">
                  <ul
                    class="d-flex"
                    v-for="(item, index) in menuItems"
                    :key="index"
                  >
                    <li>
                      <a :href="item.url">{{ item.text }}</a>
                    </li>
                  </ul>
                </form>
              </nav>
            </div>
          </div>
        </div>
      </div>
      <div class="col-12"></div>
    </div>
  </header>
</template>

<script
>
export default {
  name: "Header",
  props: ["menuItems"],
};
</script>

<style scoped lang="scss">
@import "../assets/sass/style.scss";
div .col-3,
header nav {
  color: $white;
}

.baground-lima2 {
  background-color: $lima2;
}

header li,
i {
  list-style-type: none;
  text-decoration: none;
  color: $white;
}

header li a {
  list-style-type: none;
  text-decoration: none;
  color: $shark;
}

header {
  background-image: url(../assets/img/avada-movers-homeherobackground-final.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

header a {
  padding: 0 5px;
}
</style>