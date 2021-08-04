<template>
  <main>
    <div class="wrapper">
      <section class="grid-row grid-margin align-items-center py-100">
        <div class="grid-col-4">
          <p class="ff-small-caps">QUORA</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            Improving user engagement with
            <em style="color: #be0713">comment previews</em>.
          </h1>
        </div>
        <case-meta-info
          class="grid-col-4"
          role="Designer"
          roleNotes="(with support from research and ML teams)"
          tools="Figma, React, TypeScript"
          duration="~ 1 Month (March - April 2021)"
          process="Design → Development → A/B Testing → Iterate "
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
      <article class="py-100 grid-row grid-margin">
        <aside class="pt-100">
          <side-navigation :pageLinks="pageLinks" />
        </aside>
        <section>
          <section class="pb-100">
            <div class="py-20" id="problem">
              <h2 class="ff-dm-serif fs-36">🌪 Problem</h2>
              <p class="py-20">
                Quora is a Q&A platform with a mission to share the world’s
                knowledge. All content types on quora (both long and short form
                content) contribute to this mission, however we noticed high
                quality short content did not get as much distribution on Quora
                like their long content counterparts.
              </p>
            </div>
            <div class="py-20" id="solution">
              <h2 class="ff-dm-serif fs-36">💡 Solution</h2>
              <p class="py-10">
                I explored comment previews as a way to increase user engagement
                on content, specifically short content. This resulted in a 10%
                increase in comment expands and comments from teammates
                suggested it made for a better feed experience.
              </p>
            </div>
            <figure class="pb-20">
              <div class="d-flex flex-2-col">
                <video
                  src="https://res.cloudinary.com/drsp4xifi/video/upload/v1625147927/Portfolio_v2/Feed/Screen_Recording_2021-06-28_at_10.35.32_AM_glityn.mov"
                  autoplay
                  controls
                  muted
                  class="dark-box-shadow__small img-fluid br-8"
                >
                  Your browser does not support the video tag.
                </video>
                <div>
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133771/Portfolio_v2/Comment%20Preview/Image_16_xaxhod.png"
                    alt=""
                    class="img-fluid dark-box-shadow__small br-8"
                  />
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133769/Portfolio_v2/Comment%20Preview/Image_17_jhwfwv.png"
                    alt=""
                    class="img-fluid dark-box-shadow__small br-8"
                  />
                </div>
              </div>
              <figcaption class="fs-14 fc-grey mt-20">
                <em>Comment preview variants for A/B testing.</em>
              </figcaption>
            </figure>
          </section>

          <section class="py-40">
            <h2 class="ff-dm-serif fs-36 mb-40">🚗 The Process</h2>

            <div class="" id="research">
              <h3 class="ff-small-caps mb-10">RESEARCH</h3>

              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Short content on Quora</h4>
                <p class="py-10">
                  Quora allows for both long and short-form content, however,
                  unlike long content, short content cannot be expanded. The
                  click interaction during expands is important for collecting
                  signals to learn about users preferences, which in turn
                  improves the prediction model. As short content did not need
                  to be expanded, it suffered some bias during content
                  distribution.
                </p>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">The need to remove bias</h4>
                <p class="py-10">
                  <strong>User research</strong> showed that some spaces did not
                  understand the value of their content, and seemed to associate
                  “high quality content” with longer content. The world is
                  changing and everything is moving fast. Now more than ever
                  people are condensing brilliant tips and ideas into short
                  posts. It will be naive to assume that longer means better.
                </p>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Previous comment preview experiments
                </h4>
                <p class="py-10">
                  An earlier experiment with comment previews showed promise but
                  used up significant vertical space which could be costly
                  especially on the home feed.
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625241891/Portfolio_v2/Comment%20Preview/Screen_Shot_2021-07-02_at_12.03.55_PM_b7w35u.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625241896/Portfolio_v2/Comment%20Preview/image_2_rx38ck.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em>Previous comment preview UIs.</em>
                  </figcaption>
                </figure>
              </section>
            </div>
            <div class="py-20" id="ideation">
              <h3 class="ff-small-caps mb-10">IDEATION</h3>

              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Identifying design goals</h4>
                <p class="py-10">
                  Based on research, the design goals were clear. We needed a UI
                  that would be:
                </p>
                <div class="callout-white my-20">
                  <ul>
                    <li>
                      Engaging
                      <span class="fs-14">
                        (Display a comment that the reader will appreciate based
                        on their preferences)
                      </span>
                    </li>
                    <li>
                      Dense
                      <span class="fs-14">
                        (Keep the information as short as possible, without
                        taking too much vertical space)</span
                      >
                    </li>
                  </ul>
                </div>
              </section>
            </div>
            <div class="py-20" id="design">
              <h3 class="ff-small-caps mb-10">Design</h3>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  To keep the action bar or not?
                </h4>
                <p class="py-10">
                  The action bar contained actions that could further drive
                  engagement, including showing the number of upvotes. However,
                  I chose to exclude it because it took too much vertical space
                  and opted for a text to "view more".
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628110124/Portfolio_v2/OPO/Story_1_ozxmfq.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133771/Portfolio_v2/Comment%20Preview/Image_16_xaxhod.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >An earlier design with the action bar (left) vs one of
                      the final variants without the action bar(right), leading
                      to a significant difference in height.</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Variants & weird variant names
                </h4>
                <p class="py-10">
                  With many design ideas, I settled for 3 comment preview
                  variants. Each had a unique UI, and slightly varied in height.
                  I truncated the text at one line to show a bit of the comment
                  without using too much vertical space.
                </p>
                <figure class="pt-20">
                  <div class="d-flex flex-3-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133773/Portfolio_v2/Comment%20Preview/Image_15_tib0tj.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                      <figcaption class="fs-14 fc-grey mt-20">
                        <em>Rounded-box Variant</em>
                      </figcaption>
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133771/Portfolio_v2/Comment%20Preview/Image_16_xaxhod.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                      <figcaption class="fs-14 fc-grey mt-20">
                        <em>Grey Section Variant</em>
                      </figcaption>
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625133769/Portfolio_v2/Comment%20Preview/Image_17_jhwfwv.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                      <figcaption class="fs-14 fc-grey mt-20">
                        <em>Bubble Variant</em>
                      </figcaption>
                    </div>
                  </div>
                </figure>
              </section>
            </div>
            <div class="py-20" id="development">
              <h3 class="ff-small-caps mb-10">Development</h3>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Building the variants and iterating quickly
                </h4>
                <p class="py-10">
                  I built the variants in React, using colors and fonts from the
                  Quora design system. Working with a data scientist, I set up
                  the experiment, with the relevant target and negative metrics.
                  To iterate quickly, I opted to use the first comment in the
                  comment list for the comment preview
                  <em
                    >(N.B: The existing comment list used an algorithm to rank
                    comments in a personalized way.)</em
                  >
                </p>
              </section>
            </div>
            <div class="py-20" id="ab-testing">
              <h3 class="ff-small-caps mb-10">A/B Testing</h3>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Unexpected results & multiple iterations
                </h4>
                <p class="py-10">
                  The rounded box variant had a <strong>10% increase</strong> in
                  comment expands and the least negative impact on other
                  metrics.
                </p>
                <p class="py-10">
                  Unable to mitigate the impact on negative metrics when
                  displaying comment previews on short content, we resolved to
                  replace existing comment previews on long form content for the
                  time being, as metrics showed that the new UI promoted comment
                  engagement.
                </p>
              </section>
            </div>
          </section>

          <section>
            <div class="py-20" id="final-notes">
              <h2 class="ff-dm-serif fs-36">📝 Final Notes</h2>
              <div id="next-steps" class="pt-40">
                <h3 class="ff-small-caps">NEXT STEPS</h3>
                <p class="py-10">
                  My 3rd A/B test was about being launched just as I was finishing my internship. Look out, you just might be seeing this on your Quora feeds 👀.
                </p>
              </div>
              <div class="py-40" id="takeaways">
                <h3 class="ff-small-caps">TAKEWAYS</h3>
                <p class="py-10">
                  In designing for ML-driven solutions, it is important to seek
                  ways to learn about the user. When design supports ML, it
                  makes for a more personalized user experience.
                </p>
                <p class="py-10">
                  This project was one of my first experiences with data-driven design
                  and A/B testing, and I quickly learned to always advocate for
                  the user, especially when working closely with machine learning.
                </p>
              </div>
            </div>
          </section>
        </section>
      </article>
    </div>

    <bottom-page-navigation
      nextLinkText="Aligning business and user goals with experience mapping"
      nextLinkURL="/aligning-business-and-user-goals"
      previousLinkText="A new notification system for user engagement"
      previousLinkURL="/new-notif-system"
    />
  </main>
</template>

<script>
import BottomPageNavigation from "../components/BottomPageNavigation.vue";
import CaseMetaInfo from "../components/CaseMetaInfo.vue";
import SideNavigation from "../components/SideNavigation.vue";

export default {
  components: { BottomPageNavigation, CaseMetaInfo, SideNavigation },
  data() {
    return {
      pageLinks: [
        {
          name: "Problem",
          URL: "#problem",
        },
        {
          name: "Solution",
          URL: "#solution",
        },
        {
          name: "The Process",
          URL: "",
          sublinks: [
            {
              name: "Research",
              URL: "#research",
            },
            {
              name: "Ideation",
              URL: "#ideation",
            },
            {
              name: "Design",
              URL: "#design",
            },
            {
              name: "Development",
              URL: "#development",
            },
            {
              name: "A/B Testing",
              URL: "#ab-testing",
            },
          ],
        },
        {
          name: "Final Notes",
          URL: "",
          sublinks: [
            {
              name: "Next Steps",
              URL: "#next-steps",
            },
            {
              name: "Takeaways",
              URL: "#takeaways",
            },
          ],
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
article {
  aside {
    display: none;
    color: grey;

    @include tablet {
      display: block;
      grid-column: span 2;
    }

    .my-nav {
      position: sticky;
      top: 100px;
    }
  }
  & > section {
    grid-column: span 8;
    @include tablet {
      grid-column: span 6;
    }
  }
}

.wrapper {
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
}
</style>