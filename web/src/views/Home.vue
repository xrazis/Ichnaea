<template>
  <ShapeDividerTop/>
  <section class="hero is-medium is-default is-bold">
    <div class="hero-body">
      <div class="container">
        <div class="columns is-vcentered">
          <div class="column">
            <figure class="image is-fullwidth">
              <img alt="fitness_stats" src="../assets/undraw_fitness_stats_sht6.svg">
            </figure>
          </div>
          <div class="column is-5 is-offset-1 landing-caption">
            <h1 class="title">
              Unleash your potential with <i>ichnaea</i>
            </h1>
            <p class="subtitle">Metrics and live monitoring for your athletes. <br> The future is IoT.</p>
            <router-link class="has-text-white" to="/register">
              <button class="button is-primary is-rounded">
                Register
              </button>
            </router-link>
            <router-link class="ml-2 has-text-white" to="/login">
              <button class="button is-info is-rounded">
                Login
              </button>
            </router-link>
          </div>
        </div>
      </div>
    </div>

    <div class="hero-foot">
      <footer class="footer has-background-white">
        <div class="content has-text-centered">
          <p>Ichnaea is an IoT solution that collects and analyzes body position data from athletes in real-time.</p>
          <p>Source code can be found on <a href="https://github.com/xrazis/ichnaea" target="_blank">github</a>.</p>
        </div>
      </footer>
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue'
import ShapeDividerTop from '@/components/ShapeDividerTop.vue';

export default defineComponent({
  components: {
    ShapeDividerTop
  }
});
</script>
