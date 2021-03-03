# USAA_TEST_ENV_2

This is a proof of concept for "FR Dashboard" UI ENV

### Steps to create:

1. create "package.json" > `npm init`
2. Follow https://github.com/mailgun/frontend-best-practices/blob/master/tools.md
3. npm i react prop-types jest jest-cli react-dom
4. npm i react-test-renderer babel-jest @babel/preset-env @babel/preset-react less --save-dev
   ...
5. get prettier and eslint plugin
6. `> user settings` > 'format' > format on save
7. Format each file type with `> format document` > configure > prettier
   a. There is a way to do it with .prettierrc or package.json

### TODO:

- Add Thunks/Redux
- lint on commit
- run coverage on commit
  - stop if lower than correct coverage
- ...
