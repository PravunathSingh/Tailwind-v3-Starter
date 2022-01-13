## TailwindCSS v3 CSS Starter Template (HTML)

With Version 3, TailwindCSS has gone a major upgrade and now JIT mode comes default with it.
Since Tailwind no longer uses PurgeCSS under the hood, they've renamed the "purge" option to "content" to better reflect what it’s for:

```
module.exports = {
  - purge: [
  + content: [
    // Example content paths...

    './public/**/*.html',
    './src/**/*.{js,jsx,ts,tsx,vue}',
  ],
  theme: {
    // ...
  }
  // ...
}
```

The remaining changes in tailwindCSS can be looked up in the documentation on their official website.

### Insctructions for installing this project:

1. Clone the repository
2. Open up the terminal and run the follwing commands:

- `npm install` // install all the dependencies
- `npm run dev` // start building the output.css file

3. Open up the file through live server or through your file system and get started.

#### The content path has been configured for all the .html files in the public directory, in case one needs to add other paths, they can do so in the 'content' property in tailwind.config.js file
