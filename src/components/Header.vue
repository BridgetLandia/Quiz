<template>
  <div>
  <b-nav>
    <b-nav-item active>Quizzz</b-nav-item>
    <b-nav-item>Counter: {{numTotal}}/{{numCorrect}}</b-nav-item>
  </b-nav>
</div>

</template>

<script>
export default {
    props: [
        'numCorrect',
        'numTotal'
    ]
}
</script>