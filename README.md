# Micro Frontend with React, Angular and Vue

This is a micro-frontend project combining three technologies: React, Angular, and Vue, using Webpack Module Federation. The application includes:

- **`app-shell`**: The parent application to manage the child applications `(React 18 + TypeScript)`
- **`react-child`**: A React-based child application `(React 18 + TypeScript)`
- **`vue-child`**: A Vue-based child application `(Vue 3 + TypeScript)`
- **`angular-child`**: An Angular-based child application `(Angular 16 + TypeScript)`. Currently, the microfrontend structure of Angular has limited support in newer versions.

## Usage

1. Clone this project
2. Run React child application: `cd /react-child` then `yarn install` then `yarn start`
3. Run Angular child application: `cd /angular-child` then `yarn install` then `yarn start`
4. Run Vue child application: `cd /vue-child` then `yarn install` then `yarn start`
5. Run Parent application: `cd /app-shell` then `npm install` then `yarn start`
