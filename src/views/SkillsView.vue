<template>
  <Transition name="slide" appear>
    <div class="flex flex-col 2xl:w-2/3 w-full mx-auto">
      <h1 class="text-lime-500 sr-only">Skills</h1>
      <div class="grid xl:grid-cols-4 lg:grid-cols-3 sm:grid-cols-2 grid-cols-1 gap-7">
        <div
          class="
            flex flex-col justify-between
            skill-box skill-box-lime
            drop-shadow
            text-lime-400
            md:px-5 md:py-4 px-3 py-2"
          >
          <div>
            <h2 class="h4 text-lime-400">
              Senior level skills
            </h2>
            <ul>
              <li>Vue.js</li>
              <li>TypeScript</li>
              <li>JavaScript</li>
              <li>Pinia, Vuex</li>
              <li>Vue Router</li>
              <li>HTML</li>
              <li>CSS, Sass</li>
              <li>Node.js, npm</li>
              <li>REST APIs, Axios</li>
              <li>GraphQL</li>
              <li>Design system usage</li>
              <li>Vite, Vitest</li>
              <li>Git, GitHub</li>
              <li>Agile/Jira</li>
              <li>PDF generation</li>
              <li>Prettier/ESLint</li>
            </ul>
          </div>
          <h3 class="subtitle text-lime-400">
            These skills have been put to the test in my current role
          </h3>
        </div>

        <div
          class="
            flex flex-col justify-between
            skill-box skill-box-blue
            drop-shadow
            text-sky-400
            md:px-5 md:py-4 px-3 py-2"
          >
          <div>
            <h2 class="h4 text-sky-400">Other knowledge</h2>
            <ul>
              <li>Bootstrap</li>
              <li>Tailwind CSS</li>
              <li>Firebase</li>
              <li>Vercel</li>
              <li>Wordpress</li>
              <li>Jest/Cypress</li>
              <li>SQL</li>
              <li>C#, ASP.NET MVC</li>
              <li>Procreate</li>
              <li>
                <a
                  href="https://jaewebbdevdesignreact.vercel.app/"
                  class="underline font-bold"
                >
                  React
                </a>
              </li>
              <li>Next.js</li>
              <li>Nuxt</li>
            </ul>
          </div>
          <h3 class="subtitle text-sky-400">
            These skills have been practiced through contracts, past employment, used lightly in my job, or tutorials
          </h3>
        </div>

        <div
          class="
          flex flex-col justify-between
            skill-box skill-box-lime
            drop-shadow
            text-lime-400
            md:px-5 md:py-4 px-3 py-2"
          >
          <div>
            <h2 class="h4 text-lime-400">
              Non technical skills
            </h2>
            <ul>
              <li>Fast learner</li>
              <li>Autonomous</li>
              <li>Fantastic time management skills</li>
              <li>Easy to get along with</li>
              <li>Strong problem solving skills</li>
              <li>A desire to learn, grow and improve</li>
              <li>Experience mentoring new developers</li>
              <li>Excellent verbal and written communication</li>
            </ul>
          </div>
          <h3 class="subtitle text-lime-400">
            These skills may not be technical, but really help to get the job done!
          </h3>
        </div>

        <div
          class="
            flex flex-col justify-between
            skill-box skill-box-blue
            drop-shadow
            text-sky-400
            md:px-5 md:py-4 px-3 py-2"
          >
          <div>
            <h2 class="h4 text-sky-40">Skills I'd like to learn</h2>
            <ul>
              <li>Flutter</li>
              <li>React Native</li>
              <li>Laravel</li>
              <li>GoLang</li>
              <li>Python</li>
            </ul>
          </div>
          <h3 class="subtitle text-sky-400">
            I enjoy learning new skills, frameworks, and languages
          </h3>
        </div>
      </div>
    </div>
  </Transition>
</template>

<style scoped>
li {
  margin-bottom: 0.5rem;
}
</style>
