# [0002. semi](https://github.com/Tdahuyou/prettier/tree/main/0002.%20semi)

<!-- region:toc -->
- [1. 💻 demos.1 - semi - 配置 js 语句结尾是否加分号](#1--demos1---semi---配置-js-语句结尾是否加分号)
<!-- endregion:toc -->
- semi 默认值为 true，表示格式化之后，语句结尾会自动加上分号。如果你想要让代码看起来更简洁一些，想要把语句结尾的分号给去掉，可以将 semi 配置给手动设置为 false。

## 1. 💻 demos.1 - semi - 配置 js 语句结尾是否加分号

- prettier 配置文件 .prettierrc 内容如下：

```json
{
    "semi": true
}
```

- 测试文件内容如下：

```js
console.log('semi test')
```

- 格式化之后的效果如下：

```js
console.log("semi test");
```

- 如果将 semi 配置为 false，格式化之后的效果如下：

```js
console.log("semi test")
```