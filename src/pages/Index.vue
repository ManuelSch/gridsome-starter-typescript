<template>
  <Layout>
    <g-image class="image" alt="Gridsome" src="~/assets/favicon.png" width="135" />

    <h1 class="title">{{ title }}</h1>

    <p>
      This is a starter template for Gridsome using Typescript.
      It uses <strong>wotan</strong> for command line code analisys
      and <strong>tslint</strong> for integration with vscode.
      In order to work with Visual Studio Code, you'll need to install
      <strong>TSLint</strong> and <strong>TSLint Vue</strong>
      extensions for the editor.
    </p>

    <p class="home-links">
      <a href="https://gridsome.org/docs" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script lang="ts">
  import { Component, Vue } from 'vue-property-decorator';

  @Component
  export default class HomePage extends Vue {
    public title = 'Typescript Starter for Gridsome';
  }
</script>

<style>
  .home-links a {
    margin-right: 1rem;
  }

  .image {
    display: block;
    margin: 0 auto;
  }

  .title {
    text-align: center;
    margin: 36px auto 24px;
  }
</style>
