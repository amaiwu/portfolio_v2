<template>
  <main>
    <div class="pb-200">
      <nav class="d-flex justify-content-between align-items-center">
        <nuxt-link
          to="/"
          class="
            brand_logo
            d-flex
            justify-content-between
            align-items-center
            fc-black
          "
        >
          <img src="~/assets/images/ama_memoji.png" height="60px" alt="" />
          <span>Ama</span>
        </nuxt-link>
        <ul class="list-unstyled ff-small-caps opacity-1">
          <li>
            <nuxt-link :to="{path: '/', hash:'#work'}" exact class="fc-black no-underline">
              WORK
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about" class="fc-black no-underline">
              ABOUT
            </nuxt-link>
          </li>
        </ul>
      </nav>

      <nuxt />
    </div>

    <footer class="bc-white text-center fs-14 fc-black center-box-content">
      Designed and built by Chiamaka Iwuanyanwu
    </footer>
  </main>
</template>

<style lang="scss" scoped>
nav {
  height: 80px;
  box-shadow: 0px 4px 4px #efeff2;
  padding: 0 20px;

  @include tablet {
    padding: 0 80px;
  }
}
.brand_logo {
  font-family: var(--permanent-marker);
  font-size: 24px;
  text-shadow: 3px 1px 0px #bcbec1;
  text-decoration: none;
}

ul {
  display: grid;
  grid: auto-flow / 1fr 1fr;
  gap: 40px;
}

footer {
  height: 60px;
  border-top: 0.5px solid #dcdcdc;
}
</style>
