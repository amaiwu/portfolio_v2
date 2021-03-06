<template>
  <main>
    <div class="wrapper">
      <section class="container grid-row grid-margin align-items-center py-200">
        <div class="grid-col-4">
          <p class="ff-small-caps">UX DESIGN, DEVELOPMENT & A/B TESTING</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            Improving comment engagement with <br />
            <em style="color: #be0713">comment previews</em>.
          </h1>
          <p>
            During my internship at <strong>Quora</strong>, I worked as part of
            a cross-functional <br />
            to improve the feed experience of users using comment previews.
          </p>
        </div>
        <case-meta-info
          role="Designer"
          roleNotes="(on a team with an ML engineer and a data analyst)"
          tools="Figma, React, TypeScript"
          duration="~ 1 Month"
        />
      </section>
    </div>

    <section
      style="
        background: linear-gradient(109.15deg, #1e487b 37.11%, #8e3642 99.61%);
        height: 400px;
      "
    >
      <div class="wrapper">
        <img
          src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626880154/Portfolio_v2/Group_247_bn3yit.png"
          class="w-100"
          style="object-fit: cover"
          height="400px"
        />
      </div>
    </section>
    <div class="wrapper">
      <section
        id="background"
        class="container grid-row grid-margin center-grid-content h-600 py-200"
      >
        <div class="">
          <h2 class="ff-dm-serif fs-36">BACKGROUND</h2>
          <p class="py-10">
            During my internship at Quora, I worked with the distribution team
            on a project to ensure that there was no bias on the Quora feed
            against short content. While Quora allows for both long and
            short-form content, we noticed that short content on the platform
            was not getting as much distribution.
          </p>
          <p>
            Working with a team of ML engineers and data analysts, I explored
            comment previews as a way to promote comment engagement on content
            on quora.
          </p>
        </div>
      </section>
    </div>
    <div class="wrapper">
      <section id="opo-gif" class="center-box-content pb-100">
        <figure class="d-inline-block">
          <video
            src="https://res.cloudinary.com/drsp4xifi/video/upload/v1625147927/Portfolio_v2/Feed/Screen_Recording_2021-06-28_at_10.35.32_AM_glityn.mov"
            autoplay
            controls
            muted
            height="600"
            class="dark-box-shadow__small"
          >
            Your browser does not support the video tag.
          </video>
        </figure>
      </section>
    </div>
    <div class="wrapper">
      <section
        id="discovery"
        class="container grid-row grid-margin center-grid-content pb-200"
      >
        <div class="grid-col-4">
          <h2 class="ff-dm-serif fs-36 py-10">DISCOVERY</h2>
          <!-- <p class="ff-dm-serif fs-36 py-10">
            Because short-content could not be expanded, its distribution was
            affected...
          </p> -->
          <p>
            On the Quora feed, long-form content is collapsed by default and
            expanded when a user clicks on the "read more" link. This kind of
            user interaction helps the machine learning model learn and
            consequently improves the feed experience for users. For short
            content however, this feature does not exist. The result is a
            possibly skewed prediction model that may not have enough
            information to understand users perception of short content.
          </p>
          <p class="py-10">
            As part of our efforts to mitigate this, I was tasked with
            implementing comment previews on short content. A benefit of this is
            that with increased comment engagement, we can learn more about
            content that users care for, and this in turn creates a better feed
            experience for users.
          </p>
        </div>
      </section>
    </div>

    <section id="market-research" class="pb-200 bc-white">
      <div class="wrapper">
        <div class="container grid-row px-80">
          <div class="pt-200 pb-150 heading">
            <p class="ff-dm-serif fs-36 mb-10 fc-light-blue">
              IDEATION & COMPROMISES
            </p>
            <p class="py-10">
              Keeping in mind that vertical space was important, every feature
              on the comment preview needed to serve a purpose, with the major
              aim of giving the user enough information to decide whether or not
              to keep reading.
            </p>
            <p class="ff-small-caps">To keep the action bar or not???</p>
            <p class="">
              My initial was simple - reduce the size of every comment element
              and truncate the text at two lines. However
            </p>
          </div>
        </div>
        <div class="container grid-row">
          <div class="container images d-flex flex-3-col px-124 no-wrap">
            <figure class="">
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133032/Portfolio_v2/Comment%20Preview/IMG_5750_1_1_z8mp6z.png"
                alt="a photo showing comment previews on instagram"
                class="img-fluid light-box-shadow"
                height="400px"
              />
            </figure>
            <figure class="">
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133031/Portfolio_v2/Comment%20Preview/IMG_5753_2_1_1_qkonpy.png"
                alt="a photo showing comment previews on linkedin"
                class="img-fluid light-box-shadow"
              />
            </figure>
            <figure class="">
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133029/Portfolio_v2/Comment%20Preview/IMG_5752_1_1_ispli9.png"
                alt="a photo showing comment previews on twitter"
                class="img-fluid light-box-shadow"
              />
            </figure>
          </div>
        </div>
      </div>
    </section>
    <div class="wrapper">
      <section
        id="ideation"
        class="container grid-row grid-margin center-grid-content py-200"
      >
        <div class="grid-col-4">
          <h2 class="ff-small-caps">DESIGN</h2>
          <p class="ff-dm-serif fs-36 py-10">
            We needed to optimize for clicks using a dense UI...
          </p>
          <p class="py-10">
            In designing the comment preview variants, it was important to
            display enough information to allow users to decide if they would
            want to keep reading while not taking up too much vertical space.
          </p>
          <p>
            Based on previous experiments, taking up too much vertical space
            could hurt other feed metrics.
          </p>
        </div>
        <div class="grid-col-2 use-main-grid">
          <figure>
            <img
              src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625241896/Portfolio_v2/Comment%20Preview/image_2_rx38ck.png"
              alt=""
              class="img-fluid light-box-shadow"
            />
            <figcaption class="text-center">
              <em class="fs-14"> Comment preview on long-form content</em>
            </figcaption>
          </figure>
          <figure class="mt-40">
            <img
              src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625241891/Portfolio_v2/Comment%20Preview/Screen_Shot_2021-07-02_at_12.03.55_PM_b7w35u.png"
              alt=""
              class="img-fluid light-box-shadow"
            />
            <figcaption class="text-center">
              <em class="fs-14"
                >Existing comment UI used as comment preview
              </em>
            </figcaption>
          </figure>
        </div>
      </section>
    </div>
    <div class="wrapper">
      <section
        id="testing"
        class="grid-margin fc-almost-white py-200 bold-bg-section"
      >
        <div class="container grid-row pb-100">
          <div class="px-20">
            <p class="ff-dm-serif fs-36">
              For A/B testing, I designed 3 comment preview variants...
            </p>
            <p class="py-10 opacity-faded">
              Each had a unique UI, and slightly varied in height. I truncated
              the text at one line to show a bit of the comment without using
              too much vertical space. I also removed the action bar to further
              reduce the height.
            </p>
            <p class="opacity-faded">
              The user interaction was simple - clicking on the comment preview
              expanded the comments inline on feed.
            </p>
          </div>
        </div>
        <div class="container">
          <div class="d-flex px-124 flex-3-col">
            <figure class="pt-40">
              <p class="ff-small-caps mb-40 opacity-1">
                DESIGN #1 - “ROUNDED BOX”
              </p>
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133773/Portfolio_v2/Comment%20Preview/Image_15_tib0tj.png"
                alt="image of the rounded box variant"
                class="img-fluid dark-box-shadow"
              />
              <figcaption class="mt-20">
                <p class="fs-14">
                  A large tap target embedded in the story. I had a good feeling
                  about this getting more clicks.
                </p>
              </figcaption>
            </figure>
            <figure class="pt-40">
              <p class="ff-small-caps mb-40 opacity-1">
                DESIGN #2 - “CURRENT UI”
              </p>
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133771/Portfolio_v2/Comment%20Preview/Image_16_xaxhod.png"
                alt="image of the dense version of the current UI variant"
                class="img-fluid dark-box-shadow"
              />
              <figcaption class="mt-20">
                <p class="fs-14">
                  With a similar design to the existing comment UI, is
                  identifiable as a comment.
                </p>
              </figcaption>
            </figure>
            <figure class="pt-40">
              <p class="ff-small-caps mb-40 opacity-1">DESIGN #3 - “BUBBLE”</p>
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133769/Portfolio_v2/Comment%20Preview/Image_17_jhwfwv.png"
                alt="image of the bubble variant"
                class="img-fluid dark-box-shadow"
              />
              <figcaption class="mt-20">
                <p class="fs-14">
                  This speech bubble UI is a common comment UI trend, and can be
                  easily identified as a comment/message/response.
                </p>
              </figcaption>
            </figure>
          </div>
        </div>
      </section>
    </div>
    <div class="wrapper">
      <section
        id="development"
        class="container grid-row grid-margin center-grid-content py-200"
      >
        <div class="grid-col-4">
          <h2 class="ff-small-caps">DEVELOPMENT & ITERATION #1</h2>
          <p class="py-10">
            I built the variants in React, using colors and fonts from the Quora
            design system. Working with a data scientist, I set up the
            experiment, with the relevant target and negative metrics.
          </p>
          <p class="pb-10">
            To iterate quickly, I opted to use the first comment in the comment
            list for the comment preview.
          </p>
          <p class="fs-14">
            <em
              >N.B.: The first iteration only displayed a comment preview on
              short-content.
            </em>
          </p>
        </div>
      </section>
    </div>

    <section id="iteration1" class="py-200 bc-white bold-bg-section">
      <div class="wrapper">
        <div class="container grid-row px-80 pb-100">
          <div class="text-center px-20 heading">
            <p class="ff-dm-serif fs-36 mb-10 fc-light-blue">
              The bubble variant increased comment expands
              <em class="fc-red">by 12%</em>, but negatively impacted other
              metrics.
            </p>
          </div>
        </div>

        <div class="container d-flex justify-content-center flex-3-col px-124">
          <figure>
            <p class="text-center mb-20 fs-36">😞</p>
            <img
              src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133769/Portfolio_v2/Comment%20Preview/Image_17_jhwfwv.png"
              alt="image of the bubble variant"
              class="img-fluid light-box-shadow"
            />
          </figure>
        </div>
      </div>
    </section>

    <div class="wrapper">
      <section
        id="iteration2"
        class="container grid-row grid-margin center-grid-content py-200"
      >
        <div class="grid-col-4">
          <h2 class="ff-small-caps">ITERATION #2</h2>
          <p class="ff-dm-serif fs-24 py-10">
            We iterated on the rounded-box variant...
          </p>
          <p class="pb-10">
            The <em>rounded box variant</em> had a 10% increase in comment
            expands but the least negative impact on other metrics, but this was
            not as successful as we had hoped.
          </p>
        </div>
      </section>
    </div>
    <div class="wrapper">
      <section
        id="iteration3"
        class="grid-margin fc-almost-white py-200 bold-bg-section"
      >
        <div class="container grid-row pb-100">
          <div class="px-20">
            <p class="ff-dm-serif fs-36 mb-10">And the 3rd iteration...</p>
            <p class="opacity-faded">
              Unable to mitigate the impact on negative metrics when displaying
              comment previews on short content, we resolved to replace existing
              comment previews on long form content for the time being, as
              metrics showed that
              <strong
                ><em>this UI change promoted comment engagement.</em></strong
              >
            </p>
          </div>
        </div>
        <div class="container grid-row">
          <div class="iteration3-image justify-items-center">
            <figure>
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625136399/Portfolio_v2/Comment%20Preview/Group_244_1_f44njd.png"
                alt="image of the rounded box variant"
                class="img-fluid"
              />
            </figure>
          </div>
        </div>
      </section>
    </div>

    <div class="wrapper">
      <section
        id="learnings"
        class="container grid-row grid-margin center-grid-content py-200"
      >
        <div class="grid-col-4">
          <h2 class="ff-small-caps">LEARNINGS</h2>
          <p class="ff-dm-serif fs-36 py-10">ML & design work together...</p>
          <p class="pb-10">
            In designing for ML-driven solutions, it is important to seek ways
            to learn about the user. When design supports ML, it makes for a
            more personalized user experience.
          </p>
          <p>
            This was one of my first experiences with data-driven design and A/B
            testing. A major takeaway was to, as a designer, always advocate for
            the user's experience, even when working closely with machine
            learning.
          </p>
        </div>
      </section>
    </div>

    <bottom-page-navigation
      nextLinkText="Aligning business and user goals with experience mapping."
      nextLinkURL="/aligning-business-and-user-goals-with-experience-mapping"
      previousLinkText="Designing a mobile app for gifting meals."
      previousLinkURL="/designing-a-mobile-app-for-gifting-meals"
    />
  </main>
</template>

<script>
import BottomPageNavigation from "../components/BottomPageNavigation.vue";
import CaseMetaInfo from "../components/CaseMetaInfo.vue";

export default {
  components: { BottomPageNavigation, CaseMetaInfo },
};
</script>

<style lang="scss" scoped>
#background {
  & > div {
    grid-column: 1/9;

    @include desktop {
      grid-column: 2/8;
    }
    @include large-desktop {
      grid-column: 3/7;
    }
  }
}
#discovery,
#ideation,
#learnings,
#design,
#development,
#iteration2 {
  & > div:not(.use-main-grid) {
    grid-column: 1/9;

    @include desktop {
      grid-column: 2/8;
    }
    @include large-desktop {
      grid-column: 2/6;
      padding-right: 80px;
    }
  }
}

.iteration3-image {
  grid-column: 1/9;

  @include large-desktop {
    grid-column: 3/7;
  }
}

#opo-gif {
  figure {
    position: relative;
  }
  .macbook-pro {
    width: 80%;
    @include large-desktop {
      width: unset;
      height: 600px;
    }
  }

  .gif {
    position: absolute;
    height: auto;
    top: 21px;
    width: 61%;
    left: 67px;
    @include large-desktop {
      top: 30px;
      left: 95px;
      width: 76%;
    }
  }
}

#market-research,
#iteration1 {
  .heading {
    grid-column: 1/9;

    @include desktop {
      grid-column: 2/8;
    }
    @include large-desktop {
      grid-column: 3/7;
    }
  }
  .images {
    grid-column: 1/9;

    @include desktop {
      grid-column: 2/8;
    }
  }
}

#features {
  .d-flex {
    flex-wrap: wrap;
    justify-content: center;
    gap: 40px;

    & > div {
      padding: 40px;
      width: 100%;

      @include large-desktop {
        flex: 0 0 calc(50% - 40px);
      }
    }
  }
}

.bold-bg-section {
  & > div {
    &:first-child {
      border-radius: 20px 20px 0 0;
      & > div:first-child {
        grid-column: 1/9;

        @include desktop {
          grid-column: 2/8;
        }
        @include large-desktop {
          grid-column: 3/7;
        }
      }
    }
    &:nth-child(3) {
      border-radius: 0 0 20px 20px;
    }
  }
}

#testing,
#iteration3 {
  background: linear-gradient(180deg, #22538d 0%, #1e487b 50%, #1b416f 100%);
  border-radius: 20px;
}

.pointer {
  display: none;
  @include large-desktop {
    display: inline-block;

    position: absolute;
    z-index: 200;
    bottom: -58px;
    right: -124px;
  }
}
</style>