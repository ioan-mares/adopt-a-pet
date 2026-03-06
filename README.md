# Adopt a pet

## Technical highlights

This project serves as a showcase of Clean Architecture and modern frontend patterns using Vue 3. Despite its minimalist UI, the underlying logic follows industry-standard best practices for scalability and performance.

* Composition API & Custom Hooks: All business logic is decoupled from the UI using the Composables pattern (use-pet-details.js), ensuring a modular, testable, and highly readable codebase.

* Reactive State Management: Utilizes a centralized reactive state object to manage global page data, eliminating "prop drilling" and maintaining a single source of truth.

* High-Performance Search: Implements a debounced search strategy (via Lodash) to minimize expensive re-renders and provide a fluid, lag-free filtering experience.

* Optimistic UI Updates: Features an integrated error-handling and rollback system (using deep cloning/Object.assign). This allows the UI to update instantly upon user action, significantly improving the perceived speed of the application.

* Clean Component Design: Built with atomic, reusable components (Input, Select, Card, CustomModal) designed for easy integration and consistent styling.

* Zero-Latency Interactions: The application simulates complex API interactions entirely on the client-side to demonstrate a high-performance, desktop-like web experience.

### Front-end version only

### For logging in, use any credentials

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
