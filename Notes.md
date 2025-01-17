# Tailwind Css
- An APi for design system
- It's tiny- never ship unused css again
- Responsive everything - Mobile first

- > Setting open -> crt + ,

- > Linting problem in css -> input.css
- Go to setting -> search unknow -> css Lint -> ignore

- > How to Use Tailwind Perocess
- create two folders -> (dist) (src)
- dist -> create file index.html
- src -> create file input.css
- in terminal run command -> npx tailwindcss init -> It will create a file (tailwind.config.js)
- input.css -> add 
@tailwind base;
@tailwind components;
@tailwind utilities;
- tailwind.config.js -> change content: [] with content: ["./dist/*.html"]
- run the command in terminal ->  npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch
- <link rel="stylesheet" href="./style.css">
