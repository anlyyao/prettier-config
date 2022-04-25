# prettier-config

my prettier config

Eslint + Prettier + Husky + Commitlint + Lint-staged

### Install
```javascript
    yarn add -D @anlyyao/prettier-config
```

### Usage
#### 两种使用方式
#### 第一种，在 `package.json` 中

```javascript
  {
    "prettier": "@anlyyao/prettier-config"
  }
```

#### 第二种，在 `.prettierrc.js` 中
```javascript
	module.exports = require("@anlyyao/prettier-config");
```


### 依赖库

```bash
`eslint`
`lint-staged` : 对暂存区的文件执行lint校验
```

### Install

```bash
yarn add -D @anlyyao/prettier-config
```

### Usage

#### 两种使用方式

#### 第一种，在 `package.json` 中

```json
{
  "prettier": "@anlyyao/prettier-config"
}
```

#### 第二种，在 `.prettierrc.js` 中

```javascript
module.exports = require('@anlyyao/prettier-config');
```

### test

```bash
// 代码格式化（测试，全局）
npx prettier --write .
```



### 开发

#### 备注： 如果一些特殊情况，需要跳过 `commitizen` 和 `commitlint` 两步校验，可使用命令：
```bash
git commit --no-verify -m "xxx"
```