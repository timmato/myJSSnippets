## lines to use in terminal with node

#### run a .js file such as test.js
node test

#### to call a function in a .js file
npx run-func file.js someFunction "a parameter"
##### example:
npx run-func script.js URLify "test"
the function in the .js script should look like:
module.exports.URLify = (urlString='') => {
}
