<template>
    <div>
        <h3>Vue Components Instructions</h3>
        <h4>This will contain the directions for how to add components to Laravel.</h4>
        <ol>
            <li v-for="instruct in instructions"> {{ instruct }}</li>
        </ol>

    </div>
</template>

<script>
  export default {
    name : "test",
    data() {
      return  {
        instructions: ['Create the component', 'Wire it up to vue.js', 'embed it inside your blade file', 'run a `npm run dev`',
        'possibly clear the cache with `php artisan cache:clear`, or `php artisan view:clear`', 'Open an incognito.'],
      }
    },
  }
</script>

<style scoped>

</style>