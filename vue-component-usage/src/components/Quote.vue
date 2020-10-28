<template>
  <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="panel panel-default">
          <div class="panel-body quote">
            <slot></slot>
          </div>
      </div>
      <!-- <div class="title">
          <slot name="title"></slot>
          <span style="color: #ccc"><slot name="subtitle">The Subtitle</slot></span>
      </div>
      <hr>
      <div>
          <slot></slot>
      </div> -->
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    /* div {
        border: 1px solid #ccc;
        box-shadow: 1px 1px 2px black;
        padding: 30px;
        margin: 30px auto;
        text-align: center;
    }
    h2 {
        color: red;
    }
    .title {
        font-style: italic;
    } */

    .panel-body {
        font-family: 'Arizonia', cursive;
        font-size: 24px;
        color: #6e6e6e;
    }
    .quote {
        cursor: pointer;
    }
    .quote:hover {
        background-color: #ffe2e2;
    }
</style>