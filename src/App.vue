<template>
    <div id="app">
        <Gunplas v-bind:gunplas="gunplas"/>
    </div>
</template>

<script>
    import Gunplas from './components/Gunplas';

    export default {
        name: 'app',
        components: {
            Gunplas
        },
      data() {
          return {
            gunplas: [{
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
              price: "18$"
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
