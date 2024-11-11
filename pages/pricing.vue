<script setup>
definePageMeta({
  layout: "landing",
});

const pricing = [
  {
    name: "Self-hosted",
    price: "Free",
    popular: false,
    features: [
      "Lifetime free",
      "Unlimited users",
      "Unlimited projects",
    ],
    button: {
      text: "Get Started",
      link: "/",
    },
  },
];
</script>

<template>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>Pricing</template>
      <template v-slot:desc>For now, <strong>hexr</strong> is only available self-hosted and free.</template>
    </LandingSectionhead>

    <div class="grid md:grid-cols-3 gap-10 mx-auto max-w-screen-lg mt-12">
      <div />
      <LandingPricing v-for="item of pricing" :plan="item" />
      <div />
    </div>
  </LandingContainer>
</template>
