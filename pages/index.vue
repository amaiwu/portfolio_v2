<template>
  <div class="wrapper">
    <main class="grid-margin">
      <section class="intro pt-200 center-box-content">
        <div class="text-center">
          <h1 class="ff-dm-serif fs-48">CHIAMAKA IWUANYANWU</h1>
          <p>Product Designer. Software Engineer</p>
          <img src="~/assets/svg/dashed-line__short.svg" alt="" />
        </div>
      </section>
      <section class="work pt-200" id="work">
        <h2 class="ff-small-caps text-center">WORK</h2>
        <div class="case-study grid-row px-124">
          <nuxt-link
            :to="caseStudy.pageLink"
            class="
              case-study__item
              fc-black
              no-underline
              br-20
              d-block
              bc-white
            "
            v-for="(caseStudy, i) in caseStudies"
            :key="i"
          >
            <div>
              <p class="ff-small-caps fs-14 mb-10">{{ caseStudy.tags }}</p>
              <h3 class="fs-24 ff-dm-serif" style="margin-bottom: 20px">
                {{ caseStudy.title }}
              </h3>
              <p>{{ caseStudy.previewText }}</p>
            </div>
            <figure>
              <img
                :src="caseStudy.thumbnailURL"
                class="img-fluid br-10"
                :alt="caseStudy.thumbnailAltText"
              />
            </figure>
          </nuxt-link>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  data() {
    return {
      caseStudies: [
        {
          tags: "UX DESIGN & EXPERIENCE MAPPING",
          title: `Improving user web experience using experience mapping.`,
          previewText: ` My team and I identified a more impactful direction for our project with The Ontario Pops Orchestra, which led to a full website redesign.`,
          pageLink: `/improving-the-web-experience-with-experience-mapping`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1625180988/Portfolio_v2/Group_246_1_e2cxlz.svg`,
          thumbnailAltText: `Thumbnail`,
        },
        {
          tags: "UX DESIGN, DEVELOPMENT & A/B TESTING",
          title: `Optimizing feed for short content with comment previews.`,
          previewText: `During my internship at Quora, I worked as part of a cross-functional team tasked with making the Quora feed short-content friendly.`,
          pageLink: `/optimizing-for-short-content`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/c_scale,w_800/v1625180980/Portfolio_v2/Group_247_gthloj.png`,
          thumbnailAltText: `Thumbnail`,
        },
        {
          tags: "UX DESIGN",
          title: `Designing feed for discoverability.`,
          previewText: `How can we help users find relevant content without being
          overwhelming? I tried to solve this problem for a school project.`,
          pageLink: `/designing-feed-for-discoverability`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1625180985/Portfolio_v2/Group_248_2_t6pc05.svg`,
          thumbnailAltText: `Thumbnail`,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
nav {
  display: flex;
  justify-content: space-between;
}

.logo span {
  font-size: 24px;
  text-shadow: 3px 1px 0px #bcbec1;
}

.intro {
  h1 {
    letter-spacing: 0.05em;
  }
  p {
    margin: 10px 0;
    position: relative;
  }
  img {
    margin-top: 60px;
  }
}

.work {
  display: grid;
  grid-gap: 40px;
}

.case-study {
  &__item {
    grid-column: 1 / 9;
    display: grid;
    grid: auto-flow / repeat(auto-fit, minmax(240px, 1fr));
    gap: 40px;
    padding: var(--p-40) var(--p-20);

    &:hover {
      background: var(--almost-white);
      filter: drop-shadow(0px 4px 30px #fafafb);
      transition: all 0.2s;
    }

    @include tablet {
      padding: var(--p-80);
    }
  }
}
</style>