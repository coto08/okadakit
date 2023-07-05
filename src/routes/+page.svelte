<h1> SK - Vítajte na stránke src/routes/ +page.svelte </h1>

<p>
  SK - Tento text sa však nezobrazuje na webe !!! 
</p>

<ul>
  <li>
    SK - Nainštalujte - len všeobecný popis
  </li>
  <li>
    Install @sveltejs/adapter-static and gh-pages. `npm i -D @sveltejs/adapter-static gh-pages`
  </li>
  <li>
   Update svelte.config.js by changing adapter-auto to adaptor-static.
   `import adapter from '@sveltejs/adapter-static';`
  </li>
  <li> Add the following to `src/routes/+layout.js`
    `export const prerender = true;`
  </li>
  <li>
    Add a script to package.json. `"gh-pages": "npm run build && npx gh-pages -d build"`
  </li>
  <li>
    If you are using a postcss such as Tailwind css, you need to add an empty .nojekyll file to the gh-pages branch.
  </li>
</ul>

<p>
  Now you just need to run `npm run gh-pages`.
</p>
