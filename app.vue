<template>
  <div class="font-mono">
    <NuxtRouteAnnouncer />
    <!-- <NuxtWelcome /> -->
    <Interview />
    <Footer></Footer>
  </div>
</template>

<script setup>
  useHead({
    title: 'Software Engineering Résumé Review',
    meta: [
      { name: 'description', content: 'Software Engineering Résumé Review and Job Search Strategy Consulting'},
      { name: 'author', content: 'Michael Althoff' },
      { name: 'keywords', content: 'resume, résumé, resume review, software engineering, software developer, programmer, job search strategy, job search consulting, ' },
      // { name: '', content: '' },

    ]

  })
</script>