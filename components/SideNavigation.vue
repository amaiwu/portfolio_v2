<template>
  <scrollactive class="my-nav">
    <ul class="list-unstyled py-20">
      <li v-for="(link, i) in pageLinks" :key="i" style="padding: 4px 0">
        <a
          :href="link.URL"
          class="no-underline fs-16 fc-grey scrollactive-item"
          >{{ link.name }}</a
        >
        <ul class="list-unstyled" v-if="link.sublinks">
          <li
            v-for="(sublink, i) in link.sublinks"
            :key="i"
            style="padding: 4px 0 0 20px"
          >
            <a
              :href="sublink.URL"
              class="no-underline fs-16 fc-grey scrollactive-item"
              active-class="active"
              >{{ sublink.name }}</a
            >
          </li>
        </ul>
      </li>
    </ul>
  </scrollactive>
</template>

<script>
export default {
    props: {
        pageLinks: Array
    }
}
</script>

<style lang="scss" scoped>
.is-active {
  position: relative;
  font-weight: bold;
  &::before {
    content: "👉🏾 ";
  }
}
</style>