<script>
  import Typewriter from "svelte-typewriter";
  import { concurrent } from "svelte-typewriter";
</script>

<heroSection class="flex items-center">
  <div
    class="text-3xl flex flex-col gap-4 pl-16 w-[70%] md:flex-row sm:flex-col-reverse"
  >
    <div>
      <!-- Intro -->
      <div class="px-[60px] flex gap-2">
        <span> Hi I'm</span>
        <div>
          <span class="font-['Caveat'] text-4xl">Subeksha Thapa!</span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 1213 73"
            fill="%23000"
            class="w-[auto]"
          >
            <path
              d="M1212.41 5.51c3.05 12.87-22.36 11.93-30.26 15.68-94.32 20.51-269.09 32.42-365.48 37.51-77.91 3.82-155.66 9.93-233.67 11.67-57.49 2.56-115.05-.19-172.57 1.58-121.28.91-243.17 1.88-363.69-13.33-12.51-2.64-25.8-2.92-37.77-7.45-30.66-21.42 26.02-21.53 38.52-19.26 359.95 29.05 364.68 27.36 638.24 17.85 121-3.78 241.22-19.21 426.76-41.46 4.72-.65 9.18 3.56 8.45 8.36a941.74 941.74 0 0 0 54.29-9.21c9.33-2.33 18.7-4.56 27.95-7.19a7.59 7.59 0 0 1 9.23 5.24Z"
            ></path></svg
          >
        </div>
      </div>

      <!-- Description -->
      <div class="leading-normal w-[100%]">
        <img
          src="images/message-icon.svg"
          alt=""
          class="absolute w-[4vw] h-[auto]"
        />
        <div class="relative py-[26px] pl-[60px] w-[90%] whitespace-pre-line">
          <div>
            <span> A product designer, crafting </span>
            <span class="bg-[#FFFFEC] px-2 rounded-md">user-centric</span>
            <span>and </span>
          </div>

          <div>
            <span class="bg-white px-2 rounded-md">engaging interfaces</span>
            <span>that seamlessly </span>
          </div>

          <div>
            <span class="bg-[#FBF9F1] rounded-md px-2">solve problems</span>

            <span> with a touch of fun and approachability for all</span>
          </div>
        </div>
      </div>
    </div>
    <!-- <hr /> -->
  </div>

  <div class="w-[30%] pr-16">
    <img
      src="images/dog-hero.svg"
      alt=""
      class="w-[50vw] h-[auto] object-fit"
    />
  </div>
</heroSection>
