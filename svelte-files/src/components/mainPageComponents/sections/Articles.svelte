<script lang="ts">
  import ArticelLinkBar from '../../common/ArticelLinkBar.svelte'
</script>

<section
  class="bg-white py-20 transition-colors duration-500 dark:bg-neutral-800"
>
  <div class="mx-auto max-w-5xl px-6 text-center">
    <h2 class="text-3xl font-semibold text-gray-800 dark:text-white">
      Latest Articles
    </h2>
    <div class="mt-10 flex flex-col items-center justify-center">
      <ArticelLinkBar
        title="What I Learned From 1 Year as a Software Developer"
        date="Aug 2022"
        link="https://dev.to/emmanuilsb/what-i-learned-from-1-year-as-a-software-developer-3f6g"
        first={true}
      />
      <ArticelLinkBar
        title="Stop Overcomplicating Web Development - Try Svelte"
        date="Mar 2022"
        link="https://dev.to/emmanuilsb/stop-overcomplicating-web-development-try-svelte-47ln"
      />
      <ArticelLinkBar
        title="Stop Overcomplicating your State - Try Zustand"
        date="Oct 2021"
        link="https://dev.to/emmanuilsb/stop-overcomplicating-your-state-try-zustand-39p4"
      />
    </div>
    <div class="mt-8 flex items-center justify-center">
      <a
        href="https://dev.to/emmanuilsb"
        class="mx-2 flex items-center text-gray-600 hover:text-gray-500 hover:underline dark:text-gray-300 dark:hover:text-gray-200"
      >
        <span>View More</span>
        <svg
          viewBox="0 0 120.64 122.88"
          class="ml-2 h-4 w-4"
          stroke="currentColor"
          fill="currentColor"
          ><g
            ><path
              d="M54.03,108.91c-1.55,1.63-2.31,3.74-2.28,5.85c0.03,2.11,0.84,4.2,2.44,5.79l0.12,0.12c1.58,1.5,3.6,2.23,5.61,2.2 c2.01-0.03,4.01-0.82,5.55-2.37c17.66-17.66,35.13-35.61,52.68-53.4c0.07-0.05,0.13-0.1,0.19-0.16c1.55-1.63,2.31-3.76,2.28-5.87 c-0.03-2.11-0.85-4.21-2.45-5.8l-0.27-0.26C100.43,37.47,82.98,19.87,65.46,2.36C63.93,0.82,61.93,0.03,59.92,0 c-2.01-0.03-4.03,0.7-5.61,2.21l-0.15,0.15c-1.57,1.58-2.38,3.66-2.41,5.76c-0.03,2.1,0.73,4.22,2.28,5.85l47.22,47.27 L54.03,108.91L54.03,108.91z M2.26,106.91c-1.54,1.62-2.29,3.73-2.26,5.83c0.03,2.11,0.84,4.2,2.44,5.79l0.12,0.12 c1.57,1.5,3.6,2.23,5.61,2.21c2.01-0.03,4.02-0.82,5.55-2.37C31.01,101.2,48.87,84.2,66.39,67.12c0.07-0.05,0.14-0.11,0.21-0.17 c1.55-1.63,2.31-3.76,2.28-5.87c-0.03-2.11-0.85-4.21-2.45-5.8C48.94,38.33,31.36,21.44,13.83,4.51l-0.12-0.13 c-1.53-1.54-3.53-2.32-5.54-2.35C6.16,2,4.14,2.73,2.56,4.23L2.41,4.38C0.84,5.96,0.03,8.05,0,10.14c-0.03,2.1,0.73,4.22,2.28,5.85 l47.18,45.24L2.26,106.91L2.26,106.91z"
            /></g
          ></svg
        >
      </a>
    </div>
  </div>
</section>
