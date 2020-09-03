For airbnb x prettier styles:
https://github.com/airbnb/javascript

1: Have eslint and prettier extensions installed in vscode.

2: Initialize a package.json in your project if needed.
--> npm init -y

3: Install these as dev dependencies.
--> npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node

4: Install airbnb
React:
--> npx install-peerdeps --dev eslint-config-airbnb

5: Create (or use included) Prettier config file.
--> .prettierrc

    {
        "singleQuote": true,
        // other rules here
    }

6: Create (or use included) eslint config file.
--> .eslintrc.json
or if you have eslint installed globally on your machine:
--> eslint --init

7: Check eslint config (change environment("env") as needed).

(*** Still need to organize the eslintrc file for better modularity ***)
