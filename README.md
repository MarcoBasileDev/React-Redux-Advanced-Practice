# React Redux Advanced Practice

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34)
![Static Badge](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

This project is a simple React application developed to practice Redux and Redux Toolkit. It features a dummy shopping cart where users can add products, increase or decrease their quantity, and view the total price. The application also demonstrates advanced Redux concepts such as handling asynchronous code, managing HTTP states, and using action creators with Redux Thunk. The backend is hosted on Firebase, providing a seamless integration with the front-end.

## Learning Goals

This project was developed with the primary goal of practicing and consolidating knowledge in Redux and Redux Toolkit, focusing on:

- State management with Redux Toolkit.
- Handling asynchronous code and side effects.
- Integrating backend services like Firebase.
- anaging HTTP states and feedback in Redux.
- Writing and organizing Redux actions, reducers, and middleware.

## Features

- **Product Listing:** The application displays a list of available products.
- **Add to Cart:** Users can add products to their shopping cart, which updates the cart's counter and total price.
- **View Cart:** Clicking on the cart button shows the contents of the shopping cart, allowing users to view and manage the items.
  Increase/Decrease Quantity: Users can increase or decrease the quantity of each product in the cart.
- **Asynchronous Data Fetching:** The application fetches product data from a Firebase database asynchronously.
- **Handling HTTP States:** It effectively manages loading and error states during data fetching operations.
- **Redux Toolkit Integration:** Redux Toolkit is used for state management, providing simplified syntax and usage of Action Creator Thunk.

## Technologies Used

- React
- Redux Toolkit
- Firebase

## Getting Started:

- **Clone the repository**: git clone https://github.com/MarcoBasileDev/React-Redux-Advanced-Practice.git
- **Install dependencies**: npm install
- **Run**: npm start

### Backend

- Before running the development server create a realtime database on Firebase (it is completely free).
- Create a file into the src folder named "database_url.js", and inside that file create a const DATABASE_URL where you have to put your database url.

## License

This project is licensed under the MIT License.
