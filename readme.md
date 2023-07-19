# node version 16.16.0

### Project initialization

1. 
```
    npm init -y
```

2. 
```
    npm install react react-dom
    npm install webpack webpack-cli webpack-dev-server --save-dev
    npm install babel-loader @babel/core @babel/preset-env @babel/preset-react --save-dev
```

```
    - babel-core: Chuyển đổi ES6 về ES5
    - babel-loader: Cho phép chuyển các files Javascript sử dụng Babel & Webpack
    - babel-preset-env: Gói này đơn giản là support chuyển đổi ES6, ES7, ES8, ES... về ES5.
    - babel-preset-react: Hỗ trợ chuyển đổi JSX về Javascript
```

3. 
```
    mkdir src/index.js
    mkdir public/index.html
```