# AuthFrontend

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 22.3.0.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.


1. What are the three main modern Angular features used?

Standalone Components – Make components easier to create and organize.

Signals – Make state management reactive and simple.

Built-in Control Flow – Makes templates easier to read using @if, @for, and @switch.

2. Difference between Signals and RxJS?

Signals manage application state, while RxJS handles asynchronous operations like HTTP requests and API responses.

3. Why use both auth and error interceptors?

The auth interceptor attaches JWT tokens to requests, while the error interceptor handles HTTP errors such as 401 and 403.

4. How do route guards improve security and user experience?

They prevent unauthorized users from accessing protected pages and redirect users to the correct pages.

5. What is lazy loading?

Lazy loading loads components only when needed, improving application loading speed and performance.

6. What is the single source of truth in AuthService?

AuthService centrally manages user information, tokens, login status, and authentication errors to keep data consistent.

7. What challenges did you face connecting Angular to Node.js?

I encountered API connection, CORS, and JWT authentication issues. I solved them by configuring the API URL, enabling CORS, and using HTTP interceptors.

8. How would you add a user profile editing feature?

I would create a profile component, add a Reactive Form, connect it to the backend API, and update user information using Signals.

9. What security considerations did you implement?

I used JWT authentication, route guards, input validation, HTTP interceptors, and Angular's built-in XSS protection. HttpOnly cookies would provide safer token storage than localStorage.

10. How does this project demonstrate Integrative Programming?

It combines Angular, Node.js, REST APIs, JWT, and email services to create a complete full-stack authentication system.