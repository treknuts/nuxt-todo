<template>
  <div>
      <div class="navbar navbar-dark bg-dark">
      <ul class="nav">
        <li class="nav-item text-light">
          <NuxtLink class="nav-link hover:text-yellow-400" to="/">Home</NuxtLink>
        </li>
        <li class="nav-item text-light">
          <NuxtLink class="nav-link hover:text-yellow-400" to="/about">
            About
          </NuxtLink>
        </li>
      </ul>
    </div>
    <main>
      <img src="~/assets/logo.svg" />
      <Nuxt />
    </main>
  </div>
</template>