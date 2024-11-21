
## Características

- Incrementa y decrementa el valor del contador.
- Guarda los valores en una lista para su referencia.
- Interfaz moderna y responsiva gracias a **Tailwind CSS**.

## Confirguracion de taildwind CSS

- npm install -D tailwindcss postcss autoprefixer
- npx tailwindcss init

Configura el archivo tailwind.config.js para incluir los archivos de tu proyecto:

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./index.html", "./src/**/*.{vue,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  plugins: [],
};

## Agrega las directivas de Tailwind CSS en tu archivo CSS principal
@tailwind base;
@tailwind components;
@tailwind utilities;

