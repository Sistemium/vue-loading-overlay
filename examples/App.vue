<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar navbar-dark bg-dark shadow-sm">
      <span class="navbar-brand mb-0">Vue.js Loading Overlay</span>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="https://github.com/ankurk91/vue-loading-overlay"
               target="_blank"> GitHub</a></li>
        </ul>
    </nav>
    <main class="container mt-3">
      <div class="row">
        <div class="col-md-8">
          <component-example></component-example>
          <plugin-example></plugin-example>
        </div>

        <aside class="col-md-4">
          <div class="card">
            <div class="card-header"> Links</div>
            <div class="card-body">
              <ul>
                <li><a href="https://github.com/ankurk91/vue-loading-overlay" target="_blank">GitHub</a></li>
                <li><a href="https://www.npmjs.com/package/vue-loading-overlay" target="_blank">npm</a></li>
                <li><a
                  href="https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en"
                  target="_blank">Vue.js Dev tools</a>
                </li>
              </ul>
            </div>
          </div>
        </aside>
      </div>

    </main>
  </div>
</template>

<script>
  import ComponentExample from './components/component';
  import PluginExample from './components/plugin';

  export default {
    name: 'app',
    data() {
      return {}
    },
    components: {
      ComponentExample,
      PluginExample
    },
    methods: {}
  }
</script>

