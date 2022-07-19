# Boilerplates

## React-Vite-TypeScript

A common starter with React, Vite and TypeScript

### Notes

-   This starter uses these pre-commit tools :
    -   [Husky](https://typicode.github.io/husky)
    -   [lint-staged](https://www.npmjs.com/package/lint-staged)
    -   [ESLint](https://eslint.org/)
    -   [Prettier](https://prettier.io/)
-   There is a basic CSS reset, including the most useful settings (like "box-sizing: border-box;")
-   Vitest is used for the tests and they will run in pre-push.
-   To run and watch the tests in the console, run : `yarn test`.
-   To get a coverage report while running the tests, run : `yarn coverage`. If you want to visualize the coverage report, you can run a live server (if you are using VSCode, I recommend using [this extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)) and use this url : http://127.0.0.1:5500/coverage/index.html
