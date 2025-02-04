# restaurant_management

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
# Restaurant Ordering System - Frontend

## Project Overview
The frontend of the Restaurant Ordering System is built using Vue.js. It provides an interactive user interface for customers and administrators to manage restaurant orders efficiently. The application connects to the backend via API calls and ensures a smooth ordering experience.

## Tech Stack
- **Frontend Framework**: Vue.js 3
- **State Management**: Vuex
- **Routing**: Vue Router
- **HTTP Requests**: Axios
- **UI Alerts**: vue-basic-alert

## Project Structure
```
restaurant_management/
│── src/
│── public/
│── package.json
│── vue.config.js
│── babel.config.js
│── tsconfig.json
│── README.md
```

## Installation & Setup
### Prerequisites
Make sure you have the following installed:
- Node.js (v14 or later)
- Vue CLI

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/restaurant-ordering-system.git
   cd restaurant-ordering-system/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run serve
   ```
   The app will be available at `http://localhost:8080/`.

## Build for Production
To build the frontend for production, run:
```bash
npm run build
```
This will create the production-ready files inside the `dist/` directory.

## Configuration
### Proxy Setup
The frontend is configured to proxy API requests to `http://localhost:8001`.
This is set in `vue.config.js`:
```js
  devServer: {
    proxy: {
      '/': {
        target: 'http://localhost:8001'
      }
    }
  }
```

## Linting
To check for and fix linting issues, run:
```bash
npm run lint
```

## Future Enhancements
- Improve UI/UX with additional styling.
- Implement authentication and user roles.
- Add real-time order tracking.

## License
This project is open-source and available under the MIT License.

## Contributors
- **MANNAT SOOD** 
