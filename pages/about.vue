<template>
  <div class="wrapper">
    <div class="grid-row grid-margin">
      <section class="pt-150 pr-80">
        <img
          src="https://res.cloudinary.com/drsp4xifi/image/upload/v1624893246/Portfolio_v2/About/Ellipse_75_ujgztj.png"
          height="200"
          alt="Photo of Chiamaka Iwuanyanwu in a laptop"
        />
        <div style="margin-top: 40px">
          <h1 class="ff-dm-serif fs-36">Hi! 🙂</h1>
          <p style="margin-bottom: 10px">
            My name is Chiamaka, a Product Designer and Software Engineer,
            interested in designing with data while providing value to users.
          </p>
          <p class="py-10">
            I recently completed a product design internship at Quora (January -
            April, 2021), and i'm currently in my final semester at the
            University of Toronto, where i'm studying for a Master's Degree in
            UX Design.
          </p>
          <div class="d-flex mt-40">
            <a
              href="https://www.linkedin.com/in/ChiamakaIwuanyanwu"
              target="_blank"
              class="
                no-underline
                fc-black
                fs-14
                d-flex
                align-items-center
              "
            >
              <img
                src="https://res.cloudinary.com/drsp4xifi/image/upload/v1624893325/Portfolio_v2/About/Vector_1_nmuut6.svg"
                alt="linkedIn logo"
                class="mr-10"
              /><span>Find me on linkedIn</span>
            </a>
            <!-- <div class="mx-10 fs-14">• </div>

            <a
              class="fs-14"
              href="https://res.cloudinary.com/drsp4xifi/image/upload/v1626838920/Chiamaka_s_Resume_new_2_aukeqd.pdf"
              target="_blank"
              >My Resume</a
            > -->
          </div>
        </div>
      </section>
      <section class="pt-40">
        <div>
          <h2 class="ff-small-caps">Currently Reading</h2>
          <ul class="py-20 pl-15">
            <li>Thinking with Type <em>by Ellen Lupton</em>.</li>
            <li>Animal Farm <em>by George Orwell</em>.</li>
            <li>
              Doing a lot of reading on Big Data and ML explainability, as i'm
              currently taking courses in these areas.
            </li>
          </ul>
        </div>
      </section>
      <section class="pb-40">
        <div>
          <h2 class="ff-small-caps mb-20">Been Listening to</h2>
          <a
            href="https://music.apple.com/us/album/made-in-lagos/1531532301"
            target="_blank"
            class="fc-blue"
            >Wizkid’s Made in Lagos ↗️
          </a>
        </div>
      </section>

      <section>
        <div
          class="p-10 br-4"
          style="
            background-color: #ebe9e9;
            color: #31384a;
            display: inline-block;
          "
        >
          <em class="fs-14">Updated July 1, 2021</em>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
section {
  grid-column: 1 / 9;

  @include large-desktop {
    grid-column: 2 / 7;
  }
  @include large-desktop {
    grid-column: 2 / 6;
  }
}
</style>