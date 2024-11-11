<script setup>
const features = [
  {
    title: "Choose your Large Language-Model Provider",
    description:
      "With hexr, you are not tied to a single LLM Provider. ",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "Explore your codebase",
    description:
      "Sometimes it's tedious to provide Chat-Agents all the needed content, and sometimes, you don't even know if the context is there. Let the agent do the heavy lifting.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Let AI do your coding chores",
    description:
      "Create predefined tasks and templates, that hexr can operate and execute on.",
    icon: "bx:bxs-data",
  },
  {
    title: "Free self-hosting",
    description:
      "You don't want to spend money on a subscription and feel confident to host it yourself? Go for it! hexr is open-source and free-to-use.",
    icon: "bx:bxs-bot",
  },
];
</script>

<template>
  <div class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      Let us take care of everything, or ... <br />
      host it yourself!
    </h2>
    <p class="text-lg mt-4 text-slate-600">
      <strong>hexr</strong> can be either self-hosted, or you just jump right in and let us take care of everything.
    </p>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
