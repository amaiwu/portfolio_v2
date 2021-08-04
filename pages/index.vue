<template>
  <div class="wrapper">
    <main class="grid-margin">
      <section class="intro pt-200 center-box-content">
        <div class="text-center">
          <h1 class="ff-dm-serif fs-60">CHI<em>AMAKA</em> IWUANYANWU</h1>
          <p class="fs-18 fc-grey">Product Designer</p>
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
              bc-almost-white
            "
            v-for="(caseStudy, i) in caseStudies"
            :key="i"
          >
            <div class="px-80 py-80">
              <p class="ff-small-caps fs-14 mb-10">{{ caseStudy.tags }}</p>
              <h3 class="fs-36 ff-dm-serif" style="margin-bottom: 20px">
                {{ caseStudy.title }}
              </h3>
              <p class="fs-14 fc-grey">{{ caseStudy.skills }}</p>
            </div>
            <figure :style="caseStudy.imgBackgroundColor">
              <img
                :src="caseStudy.thumbnailURL"
                class="img-fluid"
                :alt="caseStudy.thumbnailAltText"
                style="height: 100%; object-fit: cover"
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
          tags: "QUORA",
          title: `A new notification system for user engagement.`,
          pageLink: `/new-notif-system`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1627859437/Portfolio_v2/new%20notif%20system/Group_250_tost9m.png`,
          thumbnailAltText: `Thumbnail`,
          imgBackgroundColor:
            "background: linear-gradient(111.31deg, #124f3f 35.97%, #22538d 96.05%);",
          skills: "Design • Research • Documentation"
        },
           {
          tags: "QUORA",
          title: `Improving user engagement with comment previews.`,
          pageLink: `/comment-previews`,
          // pageLink: `/optimizing-feed-for-short-content`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1626880154/Portfolio_v2/Group_247_bn3yit.png`,
          thumbnailAltText: `Thumbnail`,
          imgBackgroundColor:
            "background: linear-gradient(109.15deg, #1E487B 37.11%, #8E3642 99.61%)",
          skills: "Design • Development • A/B Testing"

        },
        {
          tags: "THE ONTARIO POPS ORCHESTRA (OPO)",
          title: `Aligning business and user goals with experience mapping.`,
          // pageLink: `/aligning-business-and-user-goals-with-experience-mapping`,
          pageLink: `/aligning-business-and-user-goals`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1626834988/Portfolio_v2/Group_246-4_dy4na9.png`,
          thumbnailAltText: `Thumbnail`,
          imgBackgroundColor:
            "background: linear-gradient(251.65deg, #1e487b 37.55%, #8e3642 98.5%)",
          skills: "Design • Research • Usability Testing"

        },
        {
          tags: "PERSONAL PROJECT",
          title: `Designing a mobile app for gifting meals.`,
          pageLink: `/designing-a-mobile-app-for-gifting-meals`,
          pageLink: `/mobile-app-for-gifting-meals`,
          thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1626833562/Portfolio_v2/Group_249_e7gypf.png`,
          thumbnailAltText: `Thumbnail`,
          imgBackgroundColor:
            "background: linear-gradient(111.31deg, #124f3f 35.97%, #22538d 96.05%);",
          skills: "Design • Protoyping"

        },
     
        // {
        //   tags: "PERSONAL",
        //   title: `Designing for discoverability.`,
        //   pageLink: `/designing-for-discoverability`,
        //   thumbnailURL: `https://res.cloudinary.com/drsp4xifi/image/upload/v1626833562/Portfolio_v2/Group_248_hvmcwn.png`,
        //   thumbnailAltText: `Thumbnail`,
        //   imgBackgroundColor:
        //     "background: linear-gradient(111.31deg, #124f3f 35.97%, #22538d 96.05%);",
        //   skills: "Design • Prototyping"

        // },
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
    grid-template-columns: repeat(2, 1fr);

    // padding: var(--p-40) var(--p-20);

    &:hover {
      background: white;
      filter: drop-shadow(0px 4px 30px #fafafb);
      transition: all 0.2s;

      h3 {
        color: var(--light-blue)
      }
    }

    & > * {
      grid-column: span 2;

      @include large-desktop {
        grid-column: span 1;
        // padding: var(--p-80);
      }
    }
  }
}

figure {
  order: -1;
  height: 200px;
  border-radius: 20px 20px 0 0;

  img {
    border-radius: 20px 20px 0 0;

    @include large-desktop {
      border-radius: 0 20px 20px 0;
    }
  }

  @include large-desktop {
    border-radius: 0 20px 20px 0;
    height: unset;
    order: unset;
  }
}
</style>