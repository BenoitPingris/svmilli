Start by creating a new svelte project:

```bash
$ npx degit sveltejs/template svelte-project
$ cd svelte-project && npm i
```

Then add svmilli and milligram to your project:
```bash
$ npm i svmilli miligram
```

And finally, link the CSS sheet for milligram in your `global.css` file:

```css
@import 'milligram/dist/milligram.min.css'
```

You're ready to go !