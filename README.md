# Node TypeScript Starter

## What's preconfigured?

The intent of this starter is to be really slim so it's not a nightmare to remove or change stuff, that's why there are just a few things preconfigured:

- Babel
- TypeScript
- Husky pre-commit hook that typechecks the codebase
- A few npm scripts

## Scripts

- `yarn dev`. Runs the project in dev mode, which means that it won't check types and will restart with every change you make.
- `yarn build`. Compiles the project to the `./dist` folder.
- `yarn typecheck`. Checks the typings of the project. Gets executed before trying to create a new commit but you can also run it manually.
- `yarn start`. Runs the compiled program. Remember to execute `yarn build` before attempting to launch the program.
