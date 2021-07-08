<template>
  <main>
    <div class="wrapper">
      <section class="container grid-row grid-margin align-items-center h-600">
        <div class="grid-col-4">
          <p class="ff-small-caps">UX DESIGN, DEVELOPMENT & A/B TESTING</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            Optimizing feed for <br />
            short content with <br />
            <em style="color: #be0713">comment previews</em>.
          </h1>
          <p>
            During my internship at <strong>Quora</strong>, I worked as part of
            a cross-functional <br />
            team tasked with making the Quora feed short-content friendly.
          </p>
        </div>
        <case-meta-info
          role="Product Designer"
          roleNotes="(Team Project)"
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
          src="https://res.cloudinary.com/drsp4xifi/image/upload/c_scale,w_4000/v1625446111/Portfolio_v2/Group_247_1_ft4o6x.png"
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
          <h2 class="ff-small-caps">BACKGROUND</h2>
          <p class="ff-dm-serif fs-36 pt-10">
            Short content is not less valuable than long content...
          </p>
          <p class="py-10">
            Quora is a Q&A platform with a mission to grow the world’s
            knowledge. Though allowing for both long and short-form content, we
            noticed that short-form content on the platform was not getting as
            much distribution.
          </p>
          <p>
            Working with a team of ML engineers and data analysts, I explored
            comment previews as a way to promote comment engagement, and
            consequently collect signals to aid content distribution.
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
          <h2 class="ff-small-caps">DISCOVERY</h2>
          <p class="ff-dm-serif fs-36 py-10">
            With barely any clickable target, short-content did not get enough
            distribution...
          </p>
          <p>
            Long form content on Quora is collapsed by default to allow for more
            content on a user’s feed, which means clicking on the “more” link to
            view the full content. This click-action helps ML models in curating
            personalized feed for user.
          </p>
          <p class="py-10">
            As short content lacked this expandable ability, we looked to
            comment previews to fill the gap.
          </p>
          <p class="fs-14">
            <em
              >N.B.: For this project, short-content referred to text-only
              content that could not be expanded, and did not have any
              featurables e.g. images and links.
            </em>
          </p>
        </div>
      </section>
    </div>

    <section id="market-research" class="pb-200 bc-white">
      <div class="wrapper">
        <div class="container grid-row px-80">
          <div class="pt-200 pb-150 heading">
            <p class="ff-dm-serif fs-36 mb-10 fc-light-blue">
              HMW collect signals for short-content while providing value for
              users?
            </p>
            <p class="py-10">
              Similar platforms often show a comment preview pre-expand,
              choosing comments based on attributes such as affinity between the
              viewer and the commenter, popularity, engagement etc. to increase
              the likelihood that the comment previewed is one the user will be
              interested in.
            </p>
            <p class="">
              Features such as the commenter's name and avatar, further aid
              familiarity. All these work to improve the experience of viewers
              by highlighting content relevant to them, even among comments.
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
            Earlier experiments for comment previews had used the existing
            comment UI, but this was costly to ad revenue as it took up
            significant vertical space.
          </p>
          <p>
            Also, a dense form of a comment preview existed on long-form
            content, but it could be A LOT better.
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
              Clicking on the comment preview expanded the comments inline.
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
                  This speech bubble UI looks modern and is a common comment UI
                  trend.
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
              <em class="fc-red">by 12%</em>, but had the most negative impact
              on ad-revenue.
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
            We iterated on the rounded-box variant which had a 10% increase in
            comment expands but the least negative impact on ad revenue...
          </p>
          <p class="pb-10">
            To reduce the impact on revenue, I experimented with displaying an
            ad underneath the comment section when it is expanded. This was an
            already existing pattern for comments that I had initially
            overlooked. However, we still got pretty bad ad metrics.
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
              Unable to mitigate the impact on revenue when displaying comment
              previews on short content, we resolved to replace existing comment
              previews on long form content for the time being, as
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
            better and more personalized user experience.
          </p>
          <p>
            This was one of my first experiences with data driven design, and a
            major takeaway was to not design solely for the algorithm. It's
            important to always keep the user in mind.
          </p>
        </div>
      </section>
    </div>

    <bottom-page-navigation
      nextLinkText="Aligning business and user goals with experience mapping."
      nextLinkURL="/aligning-business-and-user-goals-with-experience-mapping"
      previousLinkText="Home"
      previousLinkURL="/"
    />
  </main>
</template>

<script>
import BottomPageNavigation from "../components/BottomPageNavigation.vue";
import CaseMetaInfo from '../components/CaseMetaInfo.vue';

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