<script lang="ts" setup>
  const items = ref([
    {
      label: 'Data',
      to: '/data'
    },
    {
      label: 'About',
      to: '/about'
    },
    {
      label: 'Contact',
      to: '/contact'
    },
  ])
</script>

<template>
  <nav class="grid">
    <div class="col logo-container flex align-items-center">
      <NuxtLink to="/" class="no-underline p-link ml-5">
        <img src="#" alt="logo placeholder" />
        <span class="ml-3">Company Name</span>
      </NuxtLink>
    </div>
    <div class="nav-links-container col">
      <ul class="list-none flex flex-row justify-content-center">
        <li class="mx-auto">
          <NuxtLink to="/" class="no-underline p-link">
            Data
          </NuxtLink>
        </li>
        <li class="mx-auto">
          <NuxtLink to="/" class="no-underline p-link">
            About
          </NuxtLink>
        </li>
        <li class="mx-auto">
          <NuxtLink to="/" class="no-underline p-link">
            Contact
          </NuxtLink>
        </li>
      </ul>
    </div>
    <div class="nav-auth-container col">
      <ul class="list-none flex flex-row justify-content-end">
        <li>
          <NuxtLink to="/" class="no-underline p-link">
            Login
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/" class="no-underline p-link mx-5">
            Register
          </NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped></style>
