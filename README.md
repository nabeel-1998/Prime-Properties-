# Tailwin CSS
I have designed website with html and css only by using Tailwind css. 
If you want to run it on your device just intsall tailwind css from https://tailwindcss.com/docs/installation.
First step: run these commands one by one on terminal by pressing ctrl+`
  npm install -D tailwindcss
  npx tailwindcss init
Now make src folder in your main folder of project and make css file name as input.css and write these lines in input.css file.
@tailwind base;
@tailwind components;
@tailwind utilities;
now again go to terminal and start compiling this:
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
if any confusioin visit here :  https://tailwindcss.com/docs/installation.
