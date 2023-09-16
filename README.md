<h1 align="center" id="title">Course-selling platform</h1>

<p id="description"><h2>Course Registration</h2> This is a course-selling platform built using React.js. <h3>Below are some of its key features:</h3> <h2>Features</h2>
    <ul>
        <li>Fully responsive Design.</li>
        <li>Prevents adding duplicate courses to the cart, providing a notification.</li>
        <li>Displays essential information:</li>
        <ol>
            <li>Total credit hours</li>
            <li>Remaining credit hours</li>
            <li>Total price</li>
        </ol>
        <li>Alerts users if the entered credit hours are less than 0 or greater than 20.</li>
    </ul> How I manage the state in this project. In this project state management is handled in the `App` component. Events occur within the `Card` child component and data updates are reflected in the `cart` component. These two components are connected within the `App` component where the state is declared and data is passed to child components via props. - <h2>Three states are maintained: </h2>
    <ul>
        <li>
            Remaining Credit: <span id="remaining-credit">0</span>
        </li>
        <li>
            Total Credit: <span id="total-credit">0</span>
        </li>
        <li>
            Total Price: <span id="total-price">$0.00</span>
        </li>
    </ul></p>

<h2>🚀 Demo</h2>

[https://course-registration-platform.vercel.app/](https://course-registration-platform.vercel.app/)

<p align="center"><img src="https://socialify.git.ci/NabilKuppu/Course-Registration-pro/image?description=1&amp;language=1&amp;name=1&amp;owner=1&amp;stargazers=1&amp;theme=Dark" alt="project-image"></p>

<p align="center"><img src="https://img.shields.io/github/license/:user/:repo" alt="shields"></p>

<h2>🛠️ Installation Steps:</h2>

<p>1. Script of create react app through vite</p>

```
npm create vite@latest course-registration -- --template react
```

<p>2. Here first of All You have to cd course-registration then write npm install at last write npm run dev in your terminal in which You can start the project in your local host</p>

```
cd course-registration  npm install npm run dev
```

<p>3. Install tailwind at first you have to command npm install -D tailwindcss postcss autoprefixer in your terminal then npx tailwindcss init -p this one</p>

```
npm install -D tailwindcss postcss autoprefixer npx tailwindcss init -p
```

<p>4. For using tailwind properly you have to add the given code in your tailwind.config .js file and as well as in the src file there is a file called index.css in where you have to write this code @tailwind base; @tailwind components; @tailwind utilities; for your convenient I Give the copy link the command</p>

```
/** @type {import('tailwindcss').Config} */ import daisyui from "daisyui"; export default {   content: ["./index.html" "./src/**/*.{jstsjsxtsx}"]   theme: {     extend: {}   }   plugins: [daisyui] };@tailwind base; @tailwind components; @tailwind utilities;
```

<p>5. Install Daisy Ui you have to run the given commnad in your terminal</p>

```
npm i -D daisyui@latest
```

<p>6. To run in properly your have to write the given code in your tailwind.config.js file more specific at first you have to import then in the plugins you have write the seond one</p>

```
import daisyui from "daisyui";  plugins: [daisyui]
```

<p>7. Prop-types command</p>

```
npm i prop-types
```

<p>8. Alert Command</p>

```
npm install sweetalert2
```

<p>9. Icons Command</p>

```
react-icons
```

<h2>💻 Built with</h2>

Technologies used in the project:

- React
- Tailwind Css
- Daisy Ui
- sweetalert2
- react-icons
- prop-types
