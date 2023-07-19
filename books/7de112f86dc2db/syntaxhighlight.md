---
title: "SyntaxHighlight の適用"
---

# Syntax Highlight を適用しよう
技術ブログを作成する場合、<code>タグに対してシンタックスハイライトを適用することで、読者の理解度を深めることができます。


```
const name = 'Jon'
const message = (name: string) => {
  console.log(`Hello! ${name}`)
}
```

```js
const name = 'Jon'
const message = (name: string) => {
  console.log(`Hello! ${name}`)
}
```

:::message
ZennはPrismを使用しており、[こちら](https://prismjs.com/#supported-languages)で対応可能な言語一覧と記述方法を確認できます。
:::