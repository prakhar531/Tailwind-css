Important steps for Tailwind CLI:

steps:
1. npm install -D tailwindcss
2. npm i vite
3. npx tailwindcss init -p
4. Config all paths in "tailwind.config.js" file. Add all file paths in content array.
5. In package.json add start script to run with vite.
"scripts": {
    "start": "vite"
}
6. npm run start

If any error occurs with autoprefixer then :
npm install -D tailwind postcss autoprefixer vite
npx tailwind init -p
