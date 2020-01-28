<template>
    <div id="app">
      {{gundam}}
    </div>
</template>

<script>
    export default {
        name: 'app',
        components: {

        },
      data() {
          return {
            gundam: [{
              id: 1,
              title: "Msn-06 Sinanju",
              price: "60$",
            },{
              id: 2,
              title: "Msn-05 Sinanju",
              price: "30$",
            },{
              id: 3,
              title: "Msn-04 Sinanju",
              price: "18$",
            }]

        }
          }
      }
</script>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
      font-family: Roboto;
      line-height: 1.4;
    }
</style>
