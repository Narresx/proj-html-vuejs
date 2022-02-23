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
                  <ul class="d-flex m-0">
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
        <div class="container pt-5 pb-5">
          <div class="row align-items-center">
            <div class="col-3">
              <img src="../assets/img/avada-movers-logo.png" />
            </div>
            <div class="col-8">
              <nav class="navbar">
                <form class="container-fluid justify-content-end">
                  <ul class="d-flex m-0">
                    <li
                      class="p-2"
                      v-for="(item, index) in menuItems"
                      :key="index"
                    >
                      <a :href="item.url">{{ item.text }}</a>
                    </li>
                  </ul>
                  <button type="button" class="rounded-pill btn-primary p-3">
                    FREE QUOTE
                  </button>
                </form>
              </nav>
            </div>
          </div>
        </div>
      </div>
      <div class="col-12 align-items-center">
        <div class="container p-5 mt-5">
          <h3 class="text-center text-color-gray pt-4 fs-5">
            MOOVING WITHOUT THE HASSLE
          </h3>
          <h2 class="text-color-shark text-center pt-3">WE MAKE IT SIMPLE</h2>
          <h3 class="text-center text-color-gray pt-3 pb-4 fs-5">
            PROFESSIONAL SERVICE WITH QUALITY AND CUSTOMERS SATISFACTION
          </h3>
        </div>
      </div>
      <div class="col-12 baground-demin2">
        <div class="text-center pt-4 pb-4">
          <a href="#" class="text-white text-decoration-none">
            <i class="fa-solid fa-paper-plane p-2">
              GET A FREE QUOTE ONLINE NOW!
            </i>
          </a>
        </div>
      </div>
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
@import "../assets/sass/_vars.scss";
div .col-3,
header nav,
span {
  color: $white;
}

.baground-lima2 {
  background-color: $lima2;
}

.baground-demin2 {
  background-color: $demin2;
}

header li,
i {
  list-style-type: none;
  color: $white;
}

header a :hover {
  color: $demin;
}

header li a {
  list-style-type: none;
  text-decoration: none;
  color: $shark;
  font-weight: bold;
}

header li,
a:hover {
  color: $lima2;
}

.col-12 div a :hover {
  transform: scale(1.3);
  color: $white;
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

.text-color-gray {
  color: $dovegray;
}

.text-color-shark {
  color: $shark;
}

button {
  font-weight: bold;
}
</style>