<template>
  <main>
    <div class="wrapper">
      <section class="grid-row grid-margin align-items-center py-100">
        <div class="grid-col-4">
          <p class="ff-small-caps">QUORA</p>
          <h1 class="ff-dm-serif fs-48 py-10">
            A new notification system for
            <em style="color: #be0713">user engagement</em>.
          </h1>
        </div>
        <case-meta-info
          class="grid-col-4"
          role="Designer"
          roleNotes="(with support from research and ML teams)"
          tools="Figma"
          duration="~ 1 Month (April 2021)"
          process="Research → Design → Documentation"
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
          src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627859437/Portfolio_v2/new%20notif%20system/Group_250_tost9m.png"
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
                knowledge. Quora notifications contribute largely to the user
                experience and are important for user engagement. However, with
                a growing team and new features (like Quora spaces),
                notifications became messy, resulting in an unpleasant scanning
                experience, mostly due to poor visual hierarchy.
              </p>
            </div>
            <div class="py-20" id="solution">
              <h2 class="ff-dm-serif fs-36">💡 Solution</h2>
              <p class="py-10">
                A notification system that is <strong>consistent</strong>,
                <strong>engaging</strong>, and <strong>actionable</strong>. The
                new notification system features improved visual hierarchy that
                aids scannability. Clearer copy to help users better understand
                the options for managing their notifications. Documentation of
                guidelines for standardizing the creation of new notifications
                by product teams.
              </p>
            </div>
            <figure class="py-40">
              <div class="d-flex flex-2-col">
                <img
                  src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627858859/Portfolio_v2/new%20notif%20system/X_-_46_pb9ibb.png"
                  alt=""
                  class="img-fluid dark-box-shadow__small"
                  style="border-radius: 8px"
                />
                <div>
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627853712/Portfolio_v2/new%20notif%20system/Frame_170_fausre.png"
                    alt=""
                    class="img-fluid dark-box-shadow__small"
                    style="border-radius: 8px"
                  />
                  <img
                    src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627919939/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_qmt8gl.png"
                    alt=""
                    class="img-fluid dark-box-shadow__small mt-20"
                    style="border-radius: 8px"
                  />
                </div>
              </div>
              <figcaption class="fs-14 fc-grey mt-20">
                <em
                  >New notification system for Quora notifications with improved
                  visual hierarchy.</em
                >
              </figcaption>
            </figure>
          </section>

          <section class="py-40">
            <h2 class="ff-dm-serif fs-36 mb-40">🚗 The Process</h2>

            <div class="" id="research">
              <h3 class="ff-small-caps">RESEARCH</h3>

              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  The role of notifications on quora
                </h4>
                <p class="py-10">
                  As a social app, notifications are essential to the quora
                  experience. They inform users of actions taken on their
                  content, and help with discovering new content. In all,
                  notifications are key for user engagement.
                </p>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  How Quora users use notifications
                </h4>
                <p class="py-10">
                  Insights from existing <strong> user research </strong>
                  revealed that quora users often used their notification feed
                  as digests. This makes sense as quora sends out personalized
                  notifications for answers and posts to users. Another insight
                  was that receiving too many unwanted notifications was a
                  trigger for users to turn off their notifications.
                </p>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  Understanding the current state of notifications
                </h4>
                <p class="py-10">
                  I carried out an audit to understand the state of quora
                  notifications. With 200+ notifications, I chose to focus on
                  notifications that were sent out most often, and also
                  identified a few notifications from each notification
                  category. Using <strong>affinity mapping</strong>, I analysed
                  notifications based on the characteristics of a typical event
                  that triggers a notification:
                </p>
                <div class="callout-white my-20">
                  <ul>
                    <li>
                      Frequency
                      <span class="fs-14">
                        (Multiple times within the hour vs Not so often
                        events)</span
                      >
                    </li>
                    <li>
                      Location
                      <span class="fs-14"
                        >(Within a <em>space</em> vs Outside a
                        <em>space</em>)</span
                      >
                    </li>
                    <li>
                      Author
                      <span class="fs-14"
                        >(System triggered vs User triggered)</span
                      >
                    </li>
                    <li>
                      Intent
                      <span class="fs-14"
                        >(Engagement notifications vs Transactional
                        notifications)</span
                      >
                    </li>
                  </ul>
                </div>
                <p class="py-10">
                  I also conducted <strong>heuristic evaluation</strong> on
                  every notification I interacted with — evaluating the journey
                  from when a notification is triggered, to when the user
                  receives and interacts with the notification. Some key
                  findings were:
                </p>
                <div class="callout-white my-20">
                  <ul>
                    <li>Most notifications lacked visual hierarchy.</li>
                    <li>
                      The clickthrough experience for some notifications was
                      poor, with users often landing on a page and not knowing
                      what they should be looking at.
                    </li>
                    <li>
                      Notifications for content with links and images were not
                      being displayed efficiently, and were confusing.
                    </li>
                  </ul>
                </div>
                <!-- INSERT IMAGES -->

                <p class="py-10">
                  These inconsistencies largely could be attributed to teams
                  owning their notifications and working in silos. Hence a
                  system was important to aid consistency.
                </p>
              </section>
            </div>
          </section>
          <section class="py-40">
            <div class="pt-20" id="ideation">
              <h3 class="ff-small-caps">IDEATION</h3>

              <section class="pt-20">
                <h4 class="ff-dm-serif fs-24">Identifying design goals</h4>
                <p class="py-10">
                  Based on my research, a system that accomodated the current
                  notifications, as well as made it easy to create new
                  notifications was needed. The design goal therein was a system
                  that was consistent, engaging and actionable.
                </p>
                <div class="callout-white my-20">
                  <ul>
                    <li>
                      Consistent
                      <span class="fs-14">
                        (A standardized system for all current and future
                        notifications)
                      </span>
                    </li>
                    <li>
                      Engaging
                      <span class="fs-14">
                        (Improved visual hierarchy to help users engage with
                        content)</span
                      >
                    </li>
                    <li>
                      Actionable
                      <span class="fs-14">
                        (Users can take action on content and give feedback as
                        needed)</span
                      >
                    </li>
                  </ul>
                </div>
              </section>
              <section class="pt-20">
                <h4 class="ff-dm-serif fs-24">Trying out ideas</h4>
                <p class="py-10">
                  I considered many UI styles, some which could not be used
                  because they shared characteristics with other content on
                  Quora, or because they did not seem to work for some
                  notifications in the same category.
                </p>
                <figure class="pb-20">
                  <div class="d-flex flex-2-col">
                    <video
                      src="https://res.cloudinary.com/drsp4xifi/video/upload/v1628111301/Portfolio_v2/OPO/Screen_Recording_2021-08-04_at_5.06.57_PM_gpysbi.mov"
                      autoplay
                      controls
                      muted
                      class="dark-box-shadow__small img-fluid br-8"
                    >
                      Your browser does not support the video tag.
                    </video>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1628111129/Portfolio_v2/OPO/Notif_item_v1_unseen_qpzbfa.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Left: Using bold text to signify that a notification has been acted on did not work for some notifications. <br> Right: A card for displaying user content looked a lot like Quora shares and could be confusing.</em
                    >
                  </figcaption>
                </figure>
              </section>
            </div>
          </section>
          <section class="py-40" id="design">
            <div class="py-20">
              <h3 class="ff-small-caps">Design</h3>

              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  Engagement Notifs vs Transactional Notif
                </h4>
                <p class="py-10">
                  The intent for engagement notifications is for users to engage
                  with content. With the content being the primary focus of the
                  notification, I made the title text bold. There was also an
                  opportunity to collect feedback from users and improve the
                  prediction model, especially in cases where a user has not
                  engaged with certain types of notifications for an extended
                  period.
                </p>
                <p class="py-10">
                  Transactional notifications on the other hand inform a user
                  that an action was taken on their content. For such
                  notifications, social interaction is the goal, so the user
                  name is highlighted to emphasize this.
                </p>
                <figure class="py-40">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627922208/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_1_bugdzu.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627922207/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_2_a51gy5.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Engagement notification (left) vs Transactional
                      notification (right).</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  Space notifs vs Null Space Notifs
                </h4>
                <p class="py-10">
                  Every piece of content on Quora either exists in a Space, or
                  outside a Space (null space). For actions taken on space
                  notifs, there are two main actors — the user that takes the
                  action and the space. Distinguishing between space and null
                  space notifications was important in aiding scannability of
                  content.
                </p>
                <figure class="py-40">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627922208/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_1_bugdzu.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627923085/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_4_rhbqdu.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Space notification (left) vs Null space notification
                      (right).</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  Real Time Notifs vs Batched Notifs
                </h4>
                <p class="py-10">
                  Similar notifications were batched to improve scannability and
                  allow users parse information quickly.
                </p>
                <figure class="py-40">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627922207/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_2_a51gy5.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627923258/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_5_zromdp.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >Real time notification (left) vs Batched notification
                      (right).</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  System Triggered Notifs vs User Triggered Notifs
                </h4>
                <p class="py-10">
                  Quora often sends out notifications to users. Such
                  notifications carry the Quora logo as the user photo. They are
                  most often engagement notifications, hence the bolded content.
                </p>
                <figure class="py-40">
                  <div class="d-flex flex-2-col">
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627923087/Portfolio_v2/new%20notif%20system/Frame_190_1_ddjxyi.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                    <div>
                      <img
                        src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627923092/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_3_milbkl.png"
                        alt=""
                        class="img-fluid dark-box-shadow__small br-8"
                      />
                    </div>
                  </div>
                  <figcaption class="fs-14 fc-grey mt-20">
                    <em
                      >System Triggered Notification (left) vs User Triggered
                      Notification (right).</em
                    >
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  Clearer Explanations for Categories
                </h4>
                <p class="py-10">
                  I added subtitles to clearly explain the options for
                  notification settings. <em>Highlights in this space</em> could
                  be misinterpreted, so I added a subtitle explaining how the
                  algorithm behind the feature works, in clear and human
                  language.
                </p>
                <figure class="py-40">
                  <div class="flex-2-col">
                    <img
                      src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627853712/Portfolio_v2/new%20notif%20system/Frame_170_fausre.png"
                      alt=""
                      class="img-fluid dark-box-shadow__small"
                      style="border-radius: 8px"
                    />
                  </div>

                  <figcaption class="fs-14 fc-grey mt-20">
                    <em>Notification settings with subtitles.</em>
                  </figcaption>
                </figure>
              </section>
              <section class="py-20">
                <h4 class="ff-dm-serif fs-24">
                  Images and Links are not left out!
                </h4>
                <p class="py-10">
                  I also created designs for images and links as these were not
                  catered to with the current system.
                </p>
                <figure class="py-40">
                  <div class="flex-2-col">
                    <img
                      src="https://res.cloudinary.com/drsp4xifi/image/upload/v1627923957/Portfolio_v2/new%20notif%20system/Notif_item_v1_unseen_6_t6et2d.png"
                      alt=""
                      class="img-fluid dark-box-shadow__small"
                      style="border-radius: 8px"
                    />
                  </div>

                  <figcaption class="fs-14 fc-grey mt-20">
                    <em>Notification with an image.</em>
                  </figcaption>
                </figure>
              </section>
              <div class="py-20" id="solution">
                <h2 class="ff-dm-serif fs-36">📝 Final Notes</h2>
                <div id="unexplored-ideas" class="pt-40">
                  <h3 class="ff-small-caps">UNEXPLORED IDEAS</h3>
                  <p class="py-10">
                    Badging was one idea that I considered but did not get
                    around to implementing given time constraints. With badging,
                    I envision an even better user experience for users in terms
                    of sc annability and recall.
                  </p>
                </div>
                <div class="py-40" id="takeaways">
                  <h3 class="ff-small-caps">TAKEWAYS</h3>
                  <p class="py-10">
                    Scaling comes with design challenges, and the impact of this
                    could result in a less than ideal user experience for
                    certain parts of the product. A design system that is well
                    documented is essential, and just as important are processes
                    that ensure that these guidelines are being enforced.
                  </p>
                </div>
              </div>
            </div>
          </section>
        </section>
      </article>
    </div>

    <bottom-page-navigation
      nextLinkText="Improving user engagement with comment previews"
      nextLinkURL="/comment-previews"
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
              name: "Unexplored Ideas",
              URL: "#unexplored-ideas",
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