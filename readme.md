## All about webpack
---

[https://webpack.js.org/](https://webpack.js.org/)

1. What is Webpack?
    - webpack does 2 main things
        - it bundles our code/assets together
        - it manages dependencies
            - makes sure code that needs to be laoded first, is, automatically

2. We've used Webpack before, with Create-React-App,
    - Behind the scenes it managed our dependencies for all our CRA projects

3. It takes all the different JS and combines into one file
    - Same with CSS

4. NPM start is what begins our webpack locally
    - if you inspect the local server you can see the main.chunk.js has all the dependency info
    - if you npm run build form therminal it creates a build folder in your root
        - this is webpack with all the code minified
