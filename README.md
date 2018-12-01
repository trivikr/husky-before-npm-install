# husky-before-npm-install

Testing the output when husky is run before npm install

- Clone this repo
- Do **not** run `npm install`
- Run following command to create index.js (or edit any file)
  ```
  echo 'console.log("Hello World");' > index.js
  ```
- `git add .`
- `git commit -m "Try running husky without node_modules"`
- Following error is displayed:
  ```
  Can't find Husky, skipping pre-commit hook
  You can reinstall it using 'npm install husky --save-dev' or delete this hook
  ```
  ![](Screenshot.png?raw=true)
