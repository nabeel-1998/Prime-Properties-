# Tailwind CSS
I have designed website with html and css only by using Tailwind css. 
If you want to run it on your device just intsall tailwind css.

Open Visual studio code and open terminal and write this command.
**'npm init -y'**
after running this command package.json file will be created.

then run this command on terminal
**'npm install tailwindcss@2.2.16'**
now create two folders named as **dest** and **src**
add style.css in src folder

add these lines in style.css
**@tailwind base;
@tailwind components;
@tailwind utilities;**

add this line in scriptts in package,json
 "build": "tailwind build src/style.css -o dest/styles.css "

Now open terminal and write this command:
**'npm run build'**

Now tailwind css will be installed in your folder.
