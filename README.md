# npm-base
A base package for creating NPM packages with typescript+eslint+prettier+jest.

# What is used
```
$ npm install typescript
$ npm install @types/node
$ npm install --save-dev eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser prettier eslint-config-prettier eslint-plugin-prettier
$ npm install --save-dev jest ts-jest @types/jest
$ npm install --save-dev ts-node
$ npm install --save-dev rimraf

$ npm ls
@cod3/npm-base@0.0.3 /pathto/npm-base
├── @types/jest@26.0.19
├── @types/node@14.14.16
├── @typescript-eslint/eslint-plugin@4.11.0
├── @typescript-eslint/parser@4.11.0
├── eslint-config-prettier@7.1.0
├── eslint-plugin-prettier@3.3.0
├── eslint@7.16.0
├── jest@26.6.3
├── prettier@2.2.1
├── rimraf@3.0.2
├── ts-jest@26.4.4
├── ts-node@9.1.1
└── typescript@4.1.3
```
# how to use
Set your .npmrc like below
```
@yourscope:registry=https://npm.pkg.github.com/
//npm.pkg.github.com/:_authToken="your PAT"
```
# References
See below for more information  
<https://docs.github.com/ja/free-pro-team@latest/packages/guides/configuring-npm-for-use-with-github-packages>

