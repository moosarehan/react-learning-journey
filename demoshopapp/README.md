# Demo Shop App

A simple e-commerce mock product manager application. The main goal of this application is to demonstrate React component decomposition, handling form inputs, state lifting, and custom formatting (such as date parsing).

## 📂 Component Hierarchy

- **`App`** - Main wrapper containing the products list state.
  - **`NewProduct`** - Container for adding a new product.
    - **`ProductForm`** - Form component that tracks inputs (Title, Price, Date) and lifts state on submit.
  - **`Products`** - Renders a collection of items wrapped inside a generic Card container.
    - **`Card`** - A reusable UI wrapper component.
    - **`ProductItem`** - Component representing a single product's detail.
      - **`ProductDate`** - Processes and formats the date structure into a readable calendar card.

## 🚀 Getting Started

Follow these steps to run the project locally:

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/moosarehan/react-learning-journey.git
    ```

2. Navigate to the project directory and install the required packages.
    ```sh
    cd react-learning-journey/demoshopapp
    npm install
    ```

3. Start the development server.
    ```sh
    npm start
    ```
