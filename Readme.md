1. do npm init

2. install babel and babel-cli globally. Babel is the compiler to compile the ES6 code to ES5.
    > `npm install -g babel babel-cli`

3. install webpack and webpac-dev-server as dedency or local modules
    > `npm install --save webpack`
    > `npm install --save webpack-dev-server`

4. install react and react-dom as dependency/local modules
    > `npm install --save react`
    > `npm install --save reac-dom`

5. install babel-core babel-loader babel-preset-react babel-preset-es2015
    > `npm install --save-dev babel-core`
    > `npm install --save-dev babel-loader`
    > `npm install --save-dev babel-preset-react`
    > `npm install --save-dev babel-preset-es2015`

6. create index.html, App.jsx, main.js and webpack.config.js files
    > `touch index.html`
    > `touch App.jsx`
    > `touch main.js`
    > `touch webpack.config.js`

7. Configure webpack
    a. input
        a. entry
    b. output
        a. path
        b. filename
    c. devServer
        a. inlineDev
        b. port
    d. modules
        a. loaders
