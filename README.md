```npx create-snowpack-app new-dir --template @snowpack/app-template-svelte-typescript
cd new-dir/
npm i -D @snowpack/plugin-sass svelte-materialify svelte-preprocess sass postcss
code .
npm start
You should see svelte icon and with fast hot reloading.
Load or enable extension: Svelte for VS Code
edit the file src/app.svelte

<script>
  import { MaterialApp, Button } from 'svelte-materialify'
</script>

<MaterialApp>
  <Button class="primary-color">Hello Materialify</Button>
</MaterialApp>
```
