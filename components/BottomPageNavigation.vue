<template>
<div class="wrapper">
   <section class="container grid-margin px-124 ">
    <img src="~assets/svg/grey-dashed-divider.svg" alt="" class="img-fluid" />
    <div class="d-flex justify-content-between pt-80 link-wrapper">
      <nuxt-link :to="previousLinkURL" class="no-underline">
        <div class="ff-small-caps d-flex opacity-1">
          <span class="p-icon pointy-arrow__left mr-10 bc-grey"></span>
          <span class="fc-grey"> PREVIOUS </span>
        </div>
        <p class="ff-dm-serif fs-24 mt-20 fc-black">{{ previousLinkText }}</p>
      </nuxt-link>
      <nuxt-link :to="nextLinkURL" class="no-underline fc-black next">
        <div class="ff-small-caps d-flex opacity-1">
          <span class="fc-grey"> NEXT </span>
          <span class="p-icon pointy-arrow__right ml-10 bc-grey"></span>
        </div>
        <p class="ff-dm-serif fs-24 mt-20 fc-black">{{ nextLinkText }}</p>
      </nuxt-link>
    </div>

    <div class="text-center pt-80">
      <nuxt-link class="ff-small-caps fc-grey opacity-1" to="/">HOME</nuxt-link>
    </div>
  </section>
</div>
 
</template>

<script>
export default {
  props: {
    previousLinkURL: String,
    previousLinkText: String,
    nextLinkURL: String,
    nextLinkText: String,
  },
};
</script>

<style lang="scss" scoped>
.link-wrapper {
  flex-wrap: wrap;
}
.d-flex {
  & a {
    flex: 0 0 100%;

    @include large-desktop {
      flex: 0 0 35%;
      flex-wrap: wrap;
    }
  }
}

.next {
  padding-bottom: 80px;
  order: -1;

  .ff-small-caps {
    @include large-desktop {
      justify-content: flex-end;
    }
  }

  @include large-desktop {
    order: 0;
    padding-bottom: 0px;
    text-align: right;
  }
}
</style>