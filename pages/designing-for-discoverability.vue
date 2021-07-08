<template>
  <main>
    <div class="wrapper">
      <section class="container grid-row grid-margin align-items-center py-200">
        <div class="grid-col-4">
          <p class="ff-small-caps">UX DESIGN</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            Designing for
            <em style="color: #114638">discoverability</em>.
          </h1>
          <p>
            How can we help users find relevant content without being
            overwhelming? I tried to solve this problem for a school project.
          </p>
        </div>
         <case-meta-info
          role="UX Designer"
          roleNotes="(Solo Project)"
          tools="Figma"
          duration="~ 2 weeks"
        />
      </section>
    </div>

    <section
      style="
        background: linear-gradient(111.31deg, #124f3f 35.97%, #22538d 96.05%);
        height: 400px;
      "
    >
      <div class="wrapper">
        <img
          src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625447079/Portfolio_v2/Group_248_otp1tp.png"
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
          <p class="ff-dm-serif fs-36 py-10">
            Pattr is a mobile app I designed to help users feel connected to
            their environment...
          </p>
          <p class="pb-10">
            It’s main idea is to curate photos and stories, with every piece of
            content connected to a location. After designing the pages for
            individual stories (inner pages), I began to explore how users will
            discover new content.
          </p>
          <p>
            The final solution was a randomized feed curated around one main
            content type - <em> stories </em>, making other content-types
            secondary and showing less often.
          </p>
        </div>
      </section>
    </div>
    <div class="wrapper">
      <section id="opo-gif" class="center-box-content pb-150 pt-150">
        <figure class="d-inline-block text-center">
          <img
            src="https://res.cloudinary.com/drsp4xifi/image/upload/c_scale,w_1876/v1625158815/Portfolio_v2/Feed/Group_245_4_xa9eo7.png"
            class="macbook-pro"
            alt="a collage of a few screens for the pattr app"
          />
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
            With multiple content types, Pattr needed entry points to aid
            discoverability...
          </p>
          <p>
            Pattr was designed to have 4 major content types - stories,
            memories, questions, nuggets. Having designed what an individual
            page for each content,
            <strong
              >I considered two main ideas - A personalized feed and
              search</strong
            >
            — both common patterns for aiding discoverability.
          </p>
        </div>
      </section>
    </div>
    <section id="market-research" class="py-200 bc-white">
      <div class="wrapper">
        <div class="container grid-row px-80">
          <div class="pb-100 fc-light-blue">
            <p class="ff-dm-serif fs-36 text-center">
              Several UI patterns are used to present content in feed
            </p>
          </div>
        </div>
        <div class="container grid-row px-124">
          <div class="grid-col-8">
            <figure class="text-center">
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625143601/Portfolio_v2/Feed/image_3_1_w0kysq.png"
                alt="a photo of the as-is experience map"
                class="light-box-shadow img-fluid"
              />
              <figcaption class="pt-40">
                <em class="text-center">
                  <strong>Quora</strong> uses carousels to help users discover
                  Spaces. They also manage different content types like posts,
                  answers, ads.
                </em>
              </figcaption>
            </figure>
            <img
              src="~assets/svg/grey-dashed-divider.svg"
              alt=""
              class="img-fluid py-80"
            />

            <figure class="text-center">
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625146393/Portfolio_v2/Feed/image_5_2_qscupb.png"
                alt="screenshots showing how medium designs for discoverability"
                class="light-box-shadow img-fluid"
              />
              <figcaption class="pt-40">
                <em class="text-center">
                  <strong>Medium</strong> also manages various content types,
                  using carousels, lists, tags to surface content. Each content
                  type also has a distinct UI.
                </em>
              </figcaption>
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
          <h2 class="ff-small-caps">IDEATION</h2>
          <p class="ff-dm-serif fs-36 py-10">
            How might we help users discover content with feeds without being
            overwhelming?
          </p>
          <p class="py-10">
            <a
              href="https://ux.shopify.com/stop-feeding-your-users-a859730a86d6"
              target="_blank"
              >Feeds can create a heavy cognitive load ↗️
            </a>
            for users given the often large amount of content they have to take
            in. This is even more strenous when there are various content types.
          </p>
          <p>
            For this project, It was important that users could distinctly
            identify each piece of content, and that content was presented in a
            way that felt natural without being overwhelming.
          </p>
        </div>
      </section>
    </div>

    <section id="testing" class="grid-margin fc-almost-white">
      <div class="wrapper">
        <div class="container grid-row py-200">
          <div class="px-124">
            <p class="ff-dm-serif fs-36 text-center">
              I considered 2 feed styles - <em>Group by category</em> and
              <em>Randomized Feed</em>.
            </p>
          </div>
          <figure class="grid-col-8 py-100 px-124">
            <img
              src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625000157/Portfolio_v2/OPO/Line_13_uykt69.svg"
              class="img-fluid"
              alt=""
            />
          </figure>
          <div class="grid-col-5 px-124">
            <div class="">
              <h4 class="ff-small-caps opacity-1">
                ❌ STYLE #1 - GROUP BY CATEGORY
              </h4>
              <p class="pt-20 pb-10 opacity-faded">
                This used 4 clearly labelled categories to help users identify
                content. A defined ending to the page controls the amount of
                information user have to consume to find information. Coupled
                with a unique UI elements for each content type, this makes the
                feed easily digestible.
              </p>
            </div>
          </div>
          <figure class="grid-col-8 px-124">
            <img
              src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625147613/Portfolio_v2/Feed/image_7_1_efdsho.png
          "
              alt=""
              class="img-fluid"
            />
          </figure>
          <div class="grid-col-8 d-flex justify-content-end flex-2-col px-124">
            <div class="">
              <p class="ff-dm-serif fs-36">
                However, finite scroll could inhibit discoverability.
              </p>
            </div>
          </div>
        </div>
        <div
          class="container grid-row px-124 py-200"
          style="border-radius: 0 0 20px 20px"
        >
          <div class="grid-col-4">
            <div class="">
              <h4 class="ff-small-caps opacity-1">
                ✅ STYLE #2 - RANDOMIZED FEED
              </h4>
              <p class="pt-20 pb-10 opacity-faded">
                I resolved to build the feed around one primary content -
                stories —, with other content types being secondary. This would
                have the benefit of allowing users scroll to explor more content
                while not overwhelming the users with different types of content
                at short intervals.
              </p>
              <p class="opacity-faded">
                Some addded benefits a randomized feed provided:
              </p>
              <ul class="opacity-faded">
                <li>A lot more real estate to show content pre-scroll.</li>
                <li>
                  Helps with alignment of focus for design as one content is now
                  primary.
                </li>
                <li>
                  Allows for ways to include other content types in future in a
                  fair manner.
                </li>
              </ul>
            </div>
          </div>
          <div class="grid-col-4 text-center">
            <video
              src="https://res.cloudinary.com/drsp4xifi/video/upload/v1625159869/Portfolio_v2/Feed/Screen_Recording_2021-06-28_at_12.10.57_AM_gyex86.mov"
              autoplay
              controls
              height="600"
              class="dark-box-shadow mt-40 br-10"
            ></video>
          </div>
        </div>
      </div>
    </section>
    <div class="wrapper">
      <section
        id="learnings"
        class="container grid-row grid-margin center-grid-content py-200"
      >
        <div class="grid-col-4">
          <h2 class="ff-small-caps">LEARNINGS & NEXT Steps</h2>
          <p class="ff-dm-serif fs-36 py-10">
            This isn’t complete without testing...
          </p>
          <p class="pb-10">
            However, I learned much about designing for discoverability for
            content based applications and the difficulties that come with
            managing multiple content types.
          </p>
          <p>
            With more time and resources, I would be interested to know how my
            assumptions fair against number of clicks on each type of content,
            and number of active minutes in the app.
          </p>
        </div>
      </section>
    </div>
    <bottom-page-navigation
      previousLinkText="Optimizing feed for short content with comment previews."
      previousLinkURL="/optimizing-feed-for-short-content"
      nextLinkText="About Me"
      nextLinkURL="/about"
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

    @include large-desktop {
      grid-column: 3/7;
    }
  }
}
#discovery,
#ideation,
#learnings,
#design {
  & > div {
    grid-column: 1/9;

    @include large-desktop {
      grid-column: 2/6;
      padding-right: 80px;
    }
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

#market-research {
  & > div > div {
    & > div:first-child {
      grid-column: 1/9;

      @include large-desktop {
        grid-column: 2/8;
      }
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

#testing {
  & > div > div {
    &:first-child,
    &:nth-child(3) {
      background: linear-gradient(
        180deg,
        #22538d 0%,
        #1e487b 50%,
        #1b416f 100%
      );
    }
    &:first-child {
      border-radius: 20px 20px 0 0;
      & > div:first-child {
        grid-column: 1/9;

        @include large-desktop {
          grid-column: 2/8;
        }
      }
    }
    &:nth-child(3) {
      border-radius: 0 0 20px 20px;
    }
    &:nth-child(2) {
      background-color: #1f497b;
    }
  }
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