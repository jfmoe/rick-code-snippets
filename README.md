# Rick - Code Snippets

<p>
<a href="https://marketplace.visualstudio.com/items?itemName=jfmoe.rick-code-snippets" target="__blank"><img src="https://img.shields.io/visual-studio-marketplace/v/jfmoe.rick-code-snippets.svg?color=4d9375&amp;label=Marketplace&logo=visual-studio-code" alt="Visual Studio Marketplace Version" /></a>
</p>

This extension contains code snippets for personal use for [Vs Code][code] editor.

## Supported languages

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)
- Html (.html)
- Vue (.vue)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Common

| Trigger | Content                                       |
| ------: | --------------------------------------------- |
|   `cl→` | `console.log(object)`                         |
|  `clo→` | `console.log('object', object);`              |
|  `imp→` | `import fs from 'fs';`                        |
|  `imd→` | `import {rename} from 'fs';`                  |
|  `imn→` | `import 'animate.css'`                        |
| `anfn→` | `(params) => {}`                              |
|  `nfn→` | `const add = (params) => {}`                  |
|  `dob→` | `const {rename} = fs`                         |
|  `dar→` | `const [first, second] = [1,2]`               |
|  `fre→` | `arrayName.forEach(element => { }`            |
|  `fof→` | `for(let itemName of objectName { }`          |
| `prom→` | `return new Promise((resolve, reject) => { }` |
| `cmmb→` | `comment block`                               |

### React

#### `rafce`

```javascript
const $1 = () => {
  return <div>$0</div>
}

export default $1
```

#### `uef`

```javascript
useEffect(() => {
  $0
}, [])
```

[code]: https://code.visualstudio.com/
