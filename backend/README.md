## Commands for Node Module
npm init
npm npm install typescript --save-dev
npm install --save-dev ts-node
npx tsc --init
npm i --save-dev @types/express
npm i -g node-ts
npm install joi

To install all Dev dependencies:

npm install --save-dev typescript
npm install --save-dev @types/bcrypt
npm install --save-dev @types/cookie-parser
npm install --save-dev @types/cors
npm install --save-dev @types/express
npm install --save-dev @types/express-serve-static-core
npm install --save-dev @types/i18n
npm install --save-dev @types/mongoose
npm install --save-dev @types/morgan
npm install --save-dev @types/node
npm install --save-dev @typescript-eslint/eslint-plugin
npm install --save-dev @typescript-eslint/parser
npm install --save-dev ts-node
npm install --save-dev tsc-alias
npm install --save-dev tsconfig-paths

## Features
- Beautiful Code as simple as possible.
- Clear Structure inspired by MVC Model.
- Localization implemention.
- Authorization CRUD example.

# express-typescript-mongoose-boilerplate

*
## Features
- Beautiful Code as simple as possible.
- Clear Structure inspired by MVC Model.
- Localization implemention.
- Authorization CRUD example.


## Scripts

All script are defined in the package-scripts.js file, but the most important ones are listed here.

### Install 
Install node-ts `npm i -g node-ts` 
Install all dependencies with `npm i`

### Linting
Run code quality analysis using `npm run lint` or `npm run lint:fix` to fix errors.




## Project Structure

```
src\
    |--mvc  
        |--models\              # Mongoose models (data layer)
        |--routes\              # Views routes
        |--controllers\         # Route controllers (controller layer)
        |--middlewares\         # Custom express middlewares
    |--helpers\             # Utility functions
    |--app.js               # Express app
    |--init\                # Init Express app
        |--locales\             # translation maps
        |--db.ts                # Init DB Connection
        |--localize.ts          # Init localization
        |--routes.ts            # Init Routes
        |--thApp.ts             # Express app
|--index.ts             # App entry point
```
