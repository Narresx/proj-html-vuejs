<template>
  <footer class="container-fluid p-0">
    <div class="height-15px baground-lima p-0"></div>
    <div class="row justify-content-center align-items-center">
      <div class="col-4 p-3">
        <h2>ABOUT</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo,
          numquam! Ducimus velit consequuntur corporis mollitia molestiae earum
          laboriosam, architecto obcaecati, doloribus, fuga porro. Ea facilis
          quisquam laborum recusandae pariatur dignissimos.
        </p>
        <img src="../assets/img/avada-movers-logo.png" />
      </div>
      <div class="col-4 p-3">
        <h2>AVADA MOVERS</h2>
        <ul>
          <li v-for="(item, index) in footerItems" :key="index">
            <a :href="item.url">{{ item.text }}</a>
          </li>
        </ul>
      </div>
      <div class="col-4 p-3">
        <h2>RECENT POSTS</h2>
        <ul>
          <li v-for="(item, index) in footerItems1" :key="index">
            <a :href="item.url">{{ item.text }}</a>
          </li>
        </ul>
      </div>
      <div class="col-12 baground-lima2">
        <nav class="navbar d-flex justify-content-center">
          <form class="container-fluid justify-content-center">
            <div class="color-white">
              <i class="fa-solid fa-copyright"></i> Copyright 2012-2020 | Avada
              Theme by ThemeFusion | All Rights Reserved | Powered by WordPress
            </div>
          </form>
          <ul class="d-flex">
            <li>
              <a href="#"><i class="fa-brands fa-facebook-f p-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa-brands fa-twitter p-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa-brands fa-instagram p-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa-brands fa-youtube p-2"></i></a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: ["footerItems", "footerItems1"],
};
</script>

<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

.baground-lima2 {
  background-color: $lima2;
}

.color-white {
  color: $white;
}

footer ul {
  padding: 0;
  margin: 0;
}

footer li,
a {
  list-style-type: none;
  text-decoration: none;
  color: $shark;
}

footer li,
i {
  color: $white;
}

footer li,
a:hover {
  color: $lima2;
}

footer a :hover {
  color: $demin;
}

.baground-lima2 {
  background-color: $lima2;
}

.baground-lima {
  background-color: $lima;
}

.height-15px {
  height: 15px;
}
</style>