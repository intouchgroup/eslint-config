## @intouchgroup/eslint-config

ESLint config for JS, JSX, TS, and TSX


### Installation
First install ESLint and this package:
```
npm i -D eslint@6.6.0 @intouchgroup/eslint-config
```

Then install *one* of the sets of optional dependencies listed below:

##### JavaScript Dependencies:
```
npm i -D babel-eslint@10.0.3
```

##### TypeScript Dependencies:
```
npm i -D typescript@3.7.2 @typescript-eslint/parser@2.7.0 @typescript-eslint/eslint-plugin@2.7.0
```

##### React JavaScript Dependencies:
```
npm i -D babel-eslint@10.0.3 eslint-plugin-react@7.16.0 eslint-plugin-react-hooks@2.2.0
```

##### React TypeScript Dependencies:
```
npm i -D typescript@3.7.2 @typescript-eslint/parser@2.7.0 @typescript-eslint/eslint-plugin@2.7.0 eslint-plugin-react@7.16.0 eslint-plugin-react-hooks@2.2.0
```


### Configuration:
Add this package to your ESLint configuration, under the `extends` property in `.eslintrc`:
```
{
    "extends": "@intouchgroup/eslint-config"
}
```


### Dependencies
##### Required:
```
eslint >=6.6.0
```

##### Optional:
```
babel-eslint >=10.0.3
eslint-plugin-react >=7.16.0
eslint-plugin-react-hooks >=2.2.0
typescript >=3.7.2
@typescript-eslint/eslint-plugin >=2.7.0
@typescript-eslint/parser >=2.7.0
```
