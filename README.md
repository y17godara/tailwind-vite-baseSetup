# tailwind-vite-baseSetup
 Base Code to Run Tailwind with Help to Node and Vite

>>>Steps to Use


>Open Terminal Run these Commands
/*Run there Commands to import files */

- npm install -D tailwindcss 
- npx tailwindcss init 
- npx tailwindcss vite
- npm install vite

>Go to "package.json" 
/* Here we are adding "scripts" section in between {} to start vite with npm */

- add
    {
    "scripts": {
    "start": "vite"
    },
    "devDependencies": {
    "tailwindcss": "^3.2.7"
    },
    "dependencies": {
    "vite": "^4.1.4"
    }
    }

> Go to "tailwind.config.js"
/* Here we are adding "*" in content */

- add
    /** @type {import('tailwindcss').Config} */
    module.exports = {
    content: ["*"],
    theme: {
        extend: {},
    },
    plugins: [],
    }
   
To Start Server () =>

>npm run

