1- npm init -y
2- npm install -D tailwindcss
3- npx tailwindcss init for create tailwind.config.js file
4- set the bellow script in package.json file :
"build": "tailwindcss -i ./src/tailwind.css -o ./dist/style.css -w"

and ...

final:
npm run build