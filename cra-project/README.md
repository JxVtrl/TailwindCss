// tailwind vite install

```
$ npx create-react-app <cra-project>
$ cd <cra-project>

$ npm install -D tailwindcss postcss autoprefixer
```

// init tailwind
```
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

// install craco
```
$ npm install -D craco
```

