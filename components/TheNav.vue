<template>
  <nav px6 py4 text-lg border="b base" flex="~ gap-2 items-center">
    <div i-logos-nuxt-icon text-4xl />
    <span text-2xl>Template</span>
    <div flex-auto />
    <ToggleTheme />
    <NuxtLink
      p2 rounded

      href="https://github.com/eeee0717/learn.nuxt.com" target="_blank"
    >
      <div i-carbon-logo-github text-2xl />
    </NuxtLink>
  </nav>
</template>
