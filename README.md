<h1 align="center" id="title">Course-selling platform</h1>

<p id="description">State Management in Course Registration Platform In this project we use React.js for building a course-selling platform. State management is essential for tracking and updating key information like remaining credit total credit hours and total price. The state is primarily managed within the App component. States Maintained Three main states are maintained to manage the core functionality of the platform: 1.remainingCredit: This state is responsible for displaying the remaining credit hours that a user has after adding courses to their cart. It helps users keep track of how many more credits they can allocate. 2.totalCredit: The totalCredit state is used to display the total number of credit hours selected by the user. It reflects the cumulative credit hours of all the courses in the cart. 3.totalPrice: This state is responsible for displaying the total price of the selected courses. Each course may have a different price and this state keeps track of the overall cost. #Component Interaction The core components involved in state management are: \*App Component: The App component is the top-level component that holds the state. It initializes the remainingCredit totalCredit and totalPrice states. It also renders child components and passes relevant data to them via props. \*Card Component: The Card component represents individual courses that users can select. It handles events like adding courses to the cart and calculating the impact on state. When a user interacts with a course card the Card component communicates with the App component to update the state. \*Cart Component: The Cart component is responsible for displaying essential information to the user such as total credit hours and total price. It receives data from the App component via props and updates its display accordingly. ##Key Features Here are some key features of the course registration platform: \*\*Responsive Design: The platform is fully responsive ensuring a seamless user experience on different devices and screen sizes. \*\*Preventing Duplicates: Users are prevented from adding duplicate courses to their cart. If they attempt to do so a notification is displayed to inform them of this restriction. \*\*Displaying Essential Information: The Cart component displays important information including the total credit hours remaining credit hours and total price. This helps users make informed decisions. \*\*Error Handling: The platform also provides error handling. If a user enters credit hours less than 0 or greater than 20 alerts are shown to notify them of these invalid inputs. By following this state management structure and component interaction pattern developers can easily grasp how the project works and make further enhancements or modifications as needed.</p>

<h2>🚀 Demo</h2>

[https://course-registration-platform.vercel.app/](https://course-registration-platform.vercel.app/)

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
