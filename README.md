This project was forked from [sakai-react](https://github.com/primefaces/sakai-react) 

which is a react based admin template, in this repo i converted the app from react to [Next.js](https://nextjs.org/)

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Folder Structure](#folder-structure)
- [Available Scripts](#available-scripts)

## Folder Structure

After creation, your project should look like this:

```
my-app/
  README.md
  node_modules/
  package.json
  public/
    favicon.ico
  pages/
    index.js
    _app.js
    _document.js
    _error.js
  src/
    logo.svg
```

Two directories pages and public at the root of your application:

- `pages` - Associated with a route based on their file name. For example pages/about.js is mapped to /about
- `public` - Stores static assets such as images, fonts, etc. Files inside public directory can then be referenced by your code starting from the base URL (/).


Next.js is built around the concept of pages. A page is a React Component exported from a .js, .jsx, .ts, or .tsx file in the `pages` directory. You can even add dynamic route parameters with the filename.

Example: If you create pages/about.js that exports a React component like below, it will be accessible at /about.

Inside the pages directory add the `index.js `file to get started. This is the page that is rendered when the user visits the root of your application.


## Available Scripts

In the project directory, you can run:

These scripts refer to the different stages of developing an application:

- dev  
      Runs `next dev` to start Next.js in development mode.
      
    Run `npm run dev` or `yarn dev `or `pnpm dev` to start the development server on http://localhost:3000

    Visit http://localhost:3000 to view your application
    
    Edit pages/index.js and see the updated result in your browser

- build  
  Runs `next build` to build the application for production usage
- start   
  Runs `next start` to start a Next.js production server
- lint  
  Runs `next lint` to set up Next.js' built-in ESLint configuration
