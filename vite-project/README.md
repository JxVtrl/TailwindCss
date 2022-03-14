// tailwind vite install

```
$ npx vite install <vite-project>
$ cd <vite-project>

$ npm install -D tailwindcss postcss autoprefixer
$ npx tailwindcss init -p
```

// add configuraiton to tailwind.config.js
```
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

// add the tailwind to css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```