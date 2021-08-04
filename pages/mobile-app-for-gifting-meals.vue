<template>
  <main>
    <div class="wrapper">
      <section class="grid-row grid-margin align-items-center py-100">
        <div class="grid-col-4">
          <p class="ff-small-caps">PERSONAL PROJECT</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            Designing a
            <em style="color: #6e4f9e">mobile app</em> for gifting meals.
          </h1>
        </div>
        <case-meta-info
          class="grid-col-4"
          role="Designer"
          roleNotes="(Personal project at the University of Toronto)"
          tools="Figma"
          duration="~ 2 weeks (April 2020)"
          process="Research → Ideation → Design"
        />
      </section>
    </div>
    <section
      style="
        background: linear-gradient(251.65deg, #1e487b 37.55%, #64509b 98.5%);
        height: 400px;
      "
    >
      <div class="wrapper">
        <img
          src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626833562/Portfolio_v2/Group_249_e7gypf.png"
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
                Food donation beneficiaries are at the mercy of whatever food is
                donated. This means they may or may not like/enjoy what is being
                offered.
              </p>
            </div>
            <div class="py-20" id="solution">
              <h2 class="ff-dm-serif fs-36">💡 Solution</h2>
              <p class="py-10">
                To improve this experience, I designed a solution that would
                connect those in need of food (beneficiaries) to those willing
                to give (givers) while allowing beneficiaries create their own
                food menus. The outcome is a happy beneficiary and a giver who
                is confident that their gift will be appreciated.
              </p>
            </div>
            <figure class="pb-20">
              <div class="d-flex flex-1-col">
                <div>
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626449798/Portfolio_v2/yours/Group_245_eirwoc.png"
                    alt=""
                    class="img-fluid dark-box-shadow__small br-8"
                  />
                </div>
              </div>
              <figcaption class="fs-14 fc-grey mt-20">
                <em>Screens from final mock-ups. Users can create a menu, buy a meal and set a goal. </em>
              </figcaption>
            </figure>
          </section>

          <section class="py-40">
            <h2 class="ff-dm-serif fs-36 mb-40">🚗 The Process</h2>

            <div class="" id="research">
              <h3 class="ff-small-caps mb-10">RESEARCH</h3>

              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Discovering the problem</h4>
                <p class="py-10">
                  At the beginning of the COVID-19 pandemic, many people were in
                  need. I witnessed someone offer a homeless person food, which
                  they rejected. This got me thinking about several things, one
                  of which was
                  <strong
                    >what if we knew exactly what people in need wanted before
                    we offered?</strong
                  >
                </p>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Building empathy with empathy mapping
                </h4>
                <p class="py-10">
                  To begin the design process, I considered 3 main stakeholders involved in food giving
                  - food beneficiaries, food givers, and food delivery services.
                  Using empathy maps I tried to better understand the
                  stakeholders involved in food donation.
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-1-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626450204/Portfolio_v2/yours/Group_265_nggjhw.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em>Very rough empathy maps for food givers and beneficiaries.</em>
                  </figcaption>
                </figure>
              </section>
            </div>
            <div class="py-20" id="ideation">
              <h3 class="ff-small-caps mb-10">IDEATION</h3>

              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Aligning focus with job stories
                </h4>
                <p class="py-10">
                  With 2 job stories, I guided the ideation process:
                </p>
                <div class="callout-white my-20">
                  <ul>
                    <li>
                      When I am hungry, I would like to eat food that I like, so
                      that actually enjoy it.
                    </li>
                    <li>
                      When I am giving, I want to know what the gift recipient
                      likes, so that I am confident that my gift is appreciated.
                    </li>
                  </ul>
                </div>
                <p class="py-10">I proceeded to pour out ideas on my wall:</p>
                <figure class="pt-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626450779/Portfolio_v2/yours/Screen_Shot_2021-07-14_at_10.22_1_mkubth.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                      <figcaption class="fs-14 fc-grey mt-20">
                        <em>Pouring out ideas on my wall.</em>
                      </figcaption>
                    </div>
                  </div>
                </figure>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Very (very) rough sketches & assumptions
                </h4>
                <p class="py-10">
                  I envisioned a solution that would have an integration with a
                  food delivery service, like UberEats. With such integration,
                  the food delivery service would provide menu options and
                  handle orders and deliveries (via APIs). On the other hand,
                  the proposed solution will focus on connecting givers to
                  beneficiaries, as well as allowing beneficiaries to curate
                  their own menus.
                </p>
                <figure class="pt-20">
                  <div class="d-flex flex-1-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626455457/Portfolio_v2/yours/Frame_265_d2qfo7.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                      <figcaption class="fs-14 fc-grey mt-20">
                        <em>Rough sketches of initial ideas.</em>
                      </figcaption>
                    </div>
                  </div>
                </figure>
              </section>
            </div>
            <div class="py-20" id="design">
              <h3 class="ff-small-caps mb-10">Design</h3>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">#1 - Create a Menu</h4>
                <p class="py-10">
                  Users (beneficiaries) can create their own menu. This was the
                  main goal of the project and this provides several benefits to
                  both parties:
                </p>
                <figure class="pt-20">
                  <div class="text-center">
                    <div class="video d-inline-block dark-box-shadow_small">
                      <video
                        src="https://res.cloudinary.com/drsp4xifi/video/upload/v1626452506/Portfolio_v2/yours/Screen_Recording_2021-07-14_at_10.51.55_PM_ei8zqn.mov"
                        autoplay
                        controls
                        height=""
                        class="500"
                        style="border-radius: 30px"
                      ></video>
                    </div>
                  </div>
                </figure>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">#2 - Buy a Meal</h4>
                <p class="py-10">
                  Givers can buy meals for beneficiaries from an already created
                  menu.
                </p>
                <p class="py-10">
                  This feature is available for users (givers) even before
                  signing in. As giving is the major goal, signing up is an
                  additional step that could prevent first time users from
                  giving. The onboarding flow prototype below shows the sign up
                  screen for givers already prompting users to buy a meal.
                </p>
                <figure class="pt-20">
                  <div class="text-center">
                    <div class="video d-inline-block dark-box-shadow_small">
                      <video
                        src="https://res.cloudinary.com/drsp4xifi/video/upload/v1626455203/Portfolio_v2/yours/Screen_Recording_2021-07-14_at_11.35.14_PM_fkfmtw.mov"
                        autoplay
                        controls
                        height=""
                        class="500"
                        style="border-radius: 30px"
                      ></video>
                    </div>
                  </div>
                </figure>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">#3 - Set a Goal</h4>
                <p class="py-10">
                  Givers can commit to giving by setting a goal, which can be a
                  budget goal or a people. With budget goals, givers can set a
                  limit for how much they want to spend giving. With people
                  goals, a goal is set for the number of individuals that the
                  giver aims to give to
                </p>
                <p class="py-10">
                  This feature was a solution to the problem of getting users to
                  give more than once, which would consequently reduce the
                  chances of using the app only once and never again.
                </p>
                <figure class="pt-20">
                  <div class="text-center">
                    <div class="video d-inline-block dark-box-shadow_small">
                      <video
                        src="https://res.cloudinary.com/drsp4xifi/video/upload/v1626455203/Portfolio_v2/yours/Untitled2_vtl535.mov"
                        autoplay
                        controls
                        height=""
                        class="500"
                        style="border-radius: 30px"
                      ></video>
                    </div>
                  </div>
                </figure>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">#4 - Onboarding Flow</h4>
                <p class="py-10">
                  With 2 main user groups onboarding was a major process in the
                  app. It was important to communicate the goals of the app, as
                  well as allow givers to buy meals without signing up.
                </p>
                <figure class="pt-20">
                  <div class="text-center">
                    <div class="video d-inline-block dark-box-shadow_small">
                      <video
                        src="https://res.cloudinary.com/drsp4xifi/video/upload/v1626455204/Portfolio_v2/yours/Screen_Recording_2021-07-15_at_11.39.16_AM_o2kgpm.mov"
                        autoplay
                        controls
                        height=""
                        class="500"
                        style="border-radius: 30px"
                      ></video>
                    </div>
                  </div>
                </figure>
              </section>
            </div>
          </section>

          <section>
            <div class="py-20" id="final-notes">
              <h2 class="ff-dm-serif fs-36">📝 Final Notes</h2>
              <div class="py-40" id="takeaways">
                <h3 class="ff-small-caps">TAKEWAYS</h3>
                <p class="py-10">
                  As this was a concept project, I made assumptions regarding
                  integrations with external food services like Ubereats.
                  However, I learned good lessons during the process, including the importance of
                  user onboarding and it's role in setting the tone for a user's
                  experience of a product. In addition, by working with 
                  apple's human interface guidelines, I learned best practices
                  for designing mobile apps.
                </p>
              </div>
            </div>
          </section>
        </section>
      </article>
    </div>

    <bottom-page-navigation
      nextLinkText="Improving comment engagement with comment previews"
      nextLinkURL="/optimizing-feed-for-short-content"
      previousLinkText="Home"
      previousLinkURL="/"
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
          ],
        },
        {
          name: "Final Notes",
          URL: "",
          sublinks: [
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