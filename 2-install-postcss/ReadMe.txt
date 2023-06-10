1- npm init -y
2- npm install -D tailwindcss postcss autoprefixer postcss-cli
3- npx tailwindcss init for create tailwind.config.js file
and create postcss.config.js file
4- set the bellow script in package.json file :
"build": "postcss ./src/tailwind.css -o ./dist/style.css -w"

5- create tailwind.config.js file
and ...

final:
npm run build