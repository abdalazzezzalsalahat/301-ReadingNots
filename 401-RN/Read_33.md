# Create a Next.js App 

> *To build a complete web application with React from scratch, there are many important details you need to consider:*


1. **bundle the code using a bundler like webpack and transformed  using a compiler like Babel.**

2. **You need to do production optimizations such as code splitting.**

3. **You might want to statically pre-render some pages for performance and SEO.**

4. **You might also want to use server-side rendering or client-side rendering.**


> *You might have to write some server-side code to connect your React app to your data store.*

## Next.js: The React Framework

> *Next.js provides a solution to all of the above problems. But more importantly, it puts you and your team in the pit of success when building React applications.*

## Setup  

> *If you don’t have Node.js installed, install it from here. You’ll need  Node.js version 10.13 or later.*


## Create a Next.js app


> To create a Next.js app, open your terminal, cd into the directory you’d like to create the app in, and run the following command:

1. `cd nextjs-blog`

2. `yarn create next-app --example with-tailwindcss Name-of-your-app`

3. `npx create-next-app name-of-your-app --use-npm --example`

## Run the development server

> *Use one of these commands to run server.*

1. `npm run dev`

2. `yarn dev`

3. `yarn start`


## Welcome to Next.js

> *You should see a page like this when you access http://localhost:3000. This is the starter template page which shows some helpful information about Next.js.*


## Styling and CSS

*Pass a string as the className prop:*

```
render() {
  return <span className="menu navigation-menu">Menu</span>
}

```

*It is common for CSS classes to depend on the component props or state:*

```
render() {
  let className = 'menu';
  if (this.props.isActive) {
    className += ' menu-active';
  }
  return <span className={className}>Menu</span>
}
```



