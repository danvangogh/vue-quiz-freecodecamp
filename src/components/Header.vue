<template>
  <b-nav tabs>
    <b-nav-item disabled>Quiz app</b-nav-item>
    <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
  </b-nav>
</template>

<script>
  export default {
    props: [
      'numCorrect',
      'numTotal'
    ]
  }
</script>
