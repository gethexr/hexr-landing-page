<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-24 md:order-1 hidden md:block">
      <img class="rounded-full transition-transform transform hover:scale-125" src="~/assets/img/hero.jpg"
        alt="AI-powered agent transforming code" loading="eager" format="avif" width="512" height="512" />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
        Let AI handle your coding chores
      </h1>
      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        Meet <strong>hexr</strong>—your open-source AI coding assistant that handles tedious code changes, breaks down
        complex tasks, and helps you understand your codebase inside out. Say goodbye to repetitive work and focus on
        what
        matters most: building and innovating.
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink href="https://github.com/hexr-ai/hexr" target="_blank" rel="noopener">Get Started</LandingLink>
        <LandingLink size="lg" styleName="outline" rel="noopener" href="https://github.com/gethexr/hexr" target="_blank">
          View Repository</LandingLink>
      </div>
    </div>
  </main>
</template>
