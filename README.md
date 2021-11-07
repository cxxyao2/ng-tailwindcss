# Ngtailwind

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.1.

# tailwindcss

- npm install -D tailwindcss
- npx tailwindcss init
- style.scss add
  - @tailwind base;
  - @tailwind components;
  - @tailwind utilities;
- tailwind.config.js add

  - module.exports = {
    > purge: {  
    > enabled: true,  
    > content: ["./src/**/*.{html,ts}"],  

},
...}
