<template>
  <main>
    <div class="wrapper">
      <section class="grid-row grid-margin align-items-center py-100">
        <div class="grid-col-4">
          <p class="ff-small-caps">THE ONTARIO POPS ORCHESTRA (OPO)</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            Aligning business and user goals with
            <em style="color: #800900">experience mapping</em>.
          </h1>
        </div>
        <case-meta-info
          class="grid-col-4"
          role="Design & Research"
          roleNotes="(all 5 team members collaborated in all phases of the project)"
          tools="Figma, Mural, Zoom, Google Forms"
          duration="~ 3 months (February - April 2021)"
          process="Research → Ideation → Design → Usability Testing"
        />
      </section>
    </div>

    <section
      style="
        background: linear-gradient(251.65deg, #1e487b 37.55%, #8e3642 98.5%);
        height: 400px;
      "
    >
      <div class="wrapper">
        <img
          src="https://res.cloudinary.com/drsp4xifi/image/upload/v1626834988/Portfolio_v2/Group_246-4_dy4na9.png"
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
                The Ontario Pops Orchestra is a non-profit Canadian Orchestra
                specializing in light-classical jazz music. Following the COVID
                19 pandemic and with concerts now online, the OPO felt there was
                an opportunity to engage with past/regular concert attendees,
                musicians, and expand the orchestra to a global audience.
              </p>
            </div>
            <div class="py-20" id="solution">
              <h2 class="ff-dm-serif fs-36">💡 Solution</h2>
              <p class="py-10">
                Using experience mapping, we reimagined the journey of a typical
                concert attendee, proposing a website redesign. The redesigned
                website is better suited for the OPO's largely elderly audience,
                features improved visual hierarchy, contains more information
                about musicians and introduces dynamic content through a social
                media feed integrated in the website.
              </p>
            </div>
            <figure class="pb-20">
              <div class="d-flex flex-2-col">
                <div>
                  <video
                    src="https://res.cloudinary.com/drsp4xifi/video/upload/v1625148306/Portfolio_v2/OPO/Screen_Recording_2021-06-28_at_10.12.22_AM_ywysqt.mov"
                    autoplay
                    muted
                    class="dark-box-shadow__small img-fluid br-8"
                  >
                    Your browser does not support the video tag.
                  </video>
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625001815/Portfolio_v2/OPO/Image_11_crt822.png"
                    alt=""
                    class="img-fluid mt-20"
                  />
                </div>

                <div>
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628097627/Portfolio_v2/OPO/OPO_Experience_Map_-_OPO_Experience_Map_-_To_Be_Draft_V4_-2_kotjvc.png"
                    alt=""
                    class="img-fluid dark-box-shadow__small br-8"
                  />
                </div>
              </div>
              <figcaption class="fs-14 fc-grey mt-20">
                <em
                  >Mock-ups from the redesign OPO website (left) and an experience map showing the future experience of an OPO attendee following the redesign (right). </em
                >
              </figcaption>
            </figure>
          </section>

          <section class="py-40">
            <h2 class="ff-dm-serif fs-36 mb-40" id="research">
              🚗 The Process
            </h2>

            <div class="">
              <h3 class="ff-small-caps mb-10">RESEARCH</h3>

              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Defining OPO's Goals</h4>
                <p class="py-10">
                  We met with the OPO to understand their goals and learned they
                  wanted to engage with former attendees, musicians, and expand
                  the orchestra to a global music community during and after the
                  COVID-19 pandemic. Through semi-structured interviews, we
                  derived insights on the OPO’s mission, revenue sources,
                  popular social media engagement metrics.
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628091060/Portfolio_v2/OPO/OPO_Business_Model_Canvas_jz2pzh.png"
                        alt=""
                        class="img-fluid br-8 dark-box-shadow__small"
                      />
                    </div>

                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628091060/Portfolio_v2/OPO/OPO_Value_Proposition_Canvas_qnzlrv.png"
                        alt=""
                        class="img-fluid br-8 dark-box-shadow__small"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Learnings from our meetings with the OPO consolidated into a Business model canvas (left) and a value prop canvas (right).</em
                    >
                  </figcaption>
                </figure>
                <p class="py-10">
                  While early conversations revolved around building an app, our
                  focus soon changed after understanding the OPO users and their
                  goals.
                </p>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Understanding OPO's audience members
                </h4>
                <p class="py-10">
                  We conducted <strong>6 user interviews</strong> with OPO concert goers to
                  better understand how connected members of the OPO community
                  felt to the OPO, due to the pandemic.
                </p>

                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628091061/Portfolio_v2/OPO/OPO_Empathy_Map_qkmeer.png"
                        alt=""
                        class="img-fluid br-8 dark-box-shadow__small"
                      />
                    </div>

                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628091061/Portfolio_v2/OPO/OPO_Persona_-_Lucy_Lopez_c129py.png"
                        alt=""
                        class="img-fluid br-8 dark-box-shadow__small"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >An empathy map (left) and a user persona (right) representing a typical OPO attendee and their pain points.</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Mapping the current experience
                </h4>
                <p class="py-10">
                  Themes from our interview data were consolidated to illustrate
                  a patron’s journey, from hearing about the OPO to forgetting
                  about the orchestra after each show. The map of the current
                  experience clearly showed that there was barely any contact
                  between the OPO and OPO attendees between concerts.
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-1-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1624995280/Portfolio_v2/OPO/Image_9_unefhs.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >An experience map showing the current journey of OPO attendees and analysing their engagement with the OPO.</em
                    >
                  </figcaption>
                </figure>
              </section>
            </div>
            <div class="py-20" id="ideation">
              <h3 class="ff-small-caps mb-10">IDEATION</h3>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Design ideas & HMWs</h4>
                <p class="py-10">
                  The website redesign focused on 3 main features:
                </p>
                <div class="callout my-20">
                  <ul>
                    <li style="list-style-type: '🎥  '">
                      <h5 class="ff-small-caps">CONCERT HIGHLIGHT REEL</h5>
                      <p class="fs-14">
                        Showcase "the OPO experience" to new attendees while
                        bringing life to the website
                      </p>
                    </li>
                    <li class="py-10" style="list-style-type: '📝  '">
                      <h5 class="ff-small-caps">MUSICIAN BIOS</h5>
                      <p class="fs-14">
                        Musicians are a major part of the OPO. This aimed to
                        build musicians' and OPO's credibility
                      </p>
                    </li>
                    <li style="list-style-type: '📱  '">
                      <h5 class="ff-small-caps">SOCIAL MEDIA INTEGRATION</h5>
                      <p class="fs-14">
                        Integrating this directly into the website would keep
                        the website fresh and lively with pictures and
                        frequently updated content, while driving traffic to the
                        OPO’s social media.
                      </p>
                    </li>
                  </ul>
                </div>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Why a website redesign?</h4>
                <div class="callout-white my-20">
                  <ul>
                    <li>
                      Experience mapping revealed opportunities for impact on
                      the website, such as a way to keep users connected to the
                      OPO.
                    </li>
                    <li>
                      The demographic of OPO attendees were largely elderly and
                      did not use mobile apps often.
                    </li>
                    <li>
                      The OPO is a non-profit, and did *not* have the technical
                      capabilities to build a mobile app.
                    </li>
                  </ul>
                </div>
              </section>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">
                  Working with technical constraints
                </h4>
                <p class="py-10">
                  A major constraint was working within the limitations of the
                  OPO’s web builder, Weebly. While we would have loved to be
                  more creative, it was most important to design a solution that
                  the OPO could implement. Hence, we did some research to ensure
                  we designed solutions that are within weebly's capabilities.
                </p>
              </section>
            </div>
            <div class="py-20" id="design">
              <h3 class="ff-small-caps mb-10">Design & Testing</h3>
              <section class="py-10">
                <h4 class="ff-dm-serif fs-24">Feature #1 - Concert Highlight Reel</h4>
                <p class="py-10">
                  The highlight reel features a gif of a typical OPO concert,
                  featuring the OPO conductor. We learned from our usability
                  tests that it was confusing having the highlight reel take up
                  the full screen height. So we reduced the height of the
                  highlight reel, allowing room to show a prominent CTA —
                  <em>Buy a ticket</em> — above the fold.
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628097505/Portfolio_v2/OPO/Screen_Shot_2021-08-04_at_1.18.19_PM_vyl20d.png"
                        alt="low fidelity mockup for musician bios"
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <video
                      src="https://res.cloudinary.com/drsp4xifi/video/upload/v1625148306/Portfolio_v2/OPO/Screen_Recording_2021-06-28_at_10.12.22_AM_ywysqt.mov"
                      autoplay
                      muted
                      class="dark-box-shadow__small img-fluid br-8"
                    >
                      Your browser does not support the video tag.
                    </video>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Low fidelity mock-up for the highlight reel (left). High fidelity mock-up with action button above the fold, following usability testing.(right)</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">Feature #2 - Musician Bios</h4>
                <p class="py-10">
                 In addition to information like name, photo and instrument
                played, users can listen to audio clips of the musicians
                playing, for a multisensory effect.
                </p>
                <p class="py-10">
                During testing, we noticed that it was not clear to users that
                the list was togglable. So I made the tap-target larger, and
                gave it a prominent background to make this more intuitive.
                </p>

                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625001800/Portfolio_v2/OPO/Image_12_yjlrfl.png"
                        alt="low fidelity mockup for musician bios"
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625001815/Portfolio_v2/OPO/Image_11_crt822.png"
                        alt="low fidelity mockup for musician bios"
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Low fidelity mock-up for musician bios (left). High fidelity mock-up with larger tap target for collapsible sections (right).</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">Feature #3 - Social Media Integration</h4>
                <p class="py-10">
                  To keep the website lively, we integrated OPO’s instagram to
                  provide dynamic content. It was the most frequently updated
                  social media and fortunately this was possible to achieve with
                  Weebly.
                </p>

                <figure class="pt-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625002327/Portfolio_v2/OPO/Image_13_barrha.png"
                        alt="low fidelity mockup for musician bios"
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Social media integration mock-up.</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">Feature #4 - Featured Artist</h4>
                <p class="py-10">
                  We identified an opportunity to further highlight the awesome
                  OPO musicians on the home page with a monthly featured artist.
                </p>

                <figure class="py-20">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1625002325/Portfolio_v2/OPO/Image_14_vumgbk.png"
                        alt="low fidelity mockup for musician bios"
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Featured artist mock-up.</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">Mapping the future experience</h4>
                <p class="py-10">
                  With the changes made to the website, the future experience of a concert attendee ends with remembering the OPO.
                </p>
                <figure class="py-20">
                  <div class="d-flex flex-1-col">
                    <img
                      src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628097627/Portfolio_v2/OPO/OPO_Experience_Map_-_OPO_Experience_Map_-_To_Be_Draft_V4_-2_kotjvc.png"
                      alt=""
                      class="img-fluid dark-box-shadow__small br-8"
                    />
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Experience map showing the future state for OPO attendees following the website redesign.</em
                    >
                  </figcaption>
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
                  The importance of talking to users cannot be over-emphasized.
                  Not only did we improve the OPO website, but we helped the OPO
                  learn about their audience. This was very rewarding!
                </p>
                <p class="py-10">
                  Also, working with clients new to UX design is a teaching
                  opportunity. With experience mapping, it was easy to bring the
                  OPO along the UX process, while serving to align our focus.
                </p>
              </div>
            </div>
          </section>
        </section>
      </article>
    </div>

    <bottom-page-navigation
      nextLinkText="Designing a mobile app for gifting meals"
      nextLinkURL="/mobile-app-for-gifting-meals"
      previousLinkText="Improving user engagement with comment previews"
      previousLinkURL="/comment-previews"
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
              name: "Design & Testing",
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
      top: 0px;
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