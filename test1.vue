<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Getting started with Vue.js</title>
  </head>
  <body>
    <div id="app">
      {{ message }}
    </div>

    <script src="https://cdn.jsdelivr.net/npm/vue"></script>
    <script>
      const app = new Vue({
        el: '#app',
        data: {
          message: 'Ahoy Vue!'
        }
      })
    </script>
  </body>
</html>