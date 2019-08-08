<template>
  <div class="container">
    <div class="row">
      <div class="col-12">
        <app-quote quote="A wonderful quote!"></app-quote>
      </div>
    </div>
  </div>
</template>

<script>
  import Quote from './components/Quotes';

  export default {
    components: {
      appQuote: Quote
    }
  }
</script>

<style>

</style>

