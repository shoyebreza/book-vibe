# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository:
    ```sh
   https://github.com/shoyebreza/book-vibe.git
    ```
2. Navigate to the project directory:
    ```sh
    cd book-vibe
    ```
3. Install the dependencies:
    ```sh
    npm install react-router-dom
    ```
4. Install the dependencies:
    ```sh
    npm install localforage match-sorter sort-by
    ```
5. Install the tailwind:
    ```sh
    npm install -D tailwindcss postcss autoprefixer
    ```
6. Initialize the tailwind:
    ```sh
    npx tailwindcss init -p
    ```
7. Install the DaisyUi:
    ```sh
    npm i -D daisyui@latest
    ```
8. Install tostify:
    ```sh
    npm i react-toastify
    ```
add plugins:
```sh
plugins: [
    require('daisyui'),
  ],
  ```
## Usage

1. Start the development server:
    ```sh
    npm run dev
    ```



