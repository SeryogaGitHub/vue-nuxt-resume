<template>
  <header class="main-header">
    <div class="center">
      <div class="flex-container align-center">
        <nav class="navigation">
          <ul>
            <li>
              <nuxt-link exact to="/" active-class='active'>Головна</nuxt-link>
            </li>
            <li>
              <nuxt-link to="portfolio" active-class='active'>Портфоліо</nuxt-link>
            </li>
            <li>
              <nuxt-link to="contacts" active-class='active'>Контакти</nuxt-link>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Navbar"
}
</script>

<style scoped>

</style>
