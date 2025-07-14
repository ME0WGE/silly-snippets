# Silly Snippets

A Visual Studio Code extension that provides a collection of **_somewhat_** useful code snippets to enhance my development experience. This project was made purely for my needs, therefore it's adapted exclusively for my coding habits.

## Features

- **Silly Code Snippets**: A curated collection of practical code snippets
- **Ultra Easy Integration**: Seamlessly integrates with VS Code's snippet system _(try not to break VSCode challenge)_
- **Customizable**: Add your own silly snippets to the collection
- **Cross-Language Support**: Snippets available for multiple programming languages _(as of v1.0, mainly **JavaScript**)_

## Supported Languages

- _The OG_ | **`JavaScript`**
- _JavaScript and HTML's bastard son_ | **`JSX`**
- _JavaScript's authoritarian cousin_ | **`TypeScript`**
- _And finally_ | **`TSX`**

## Requirements

- 5+ years of coding experience
- Visual Studio Code version `^1.102.0`

## Usage

Type the prefix and hit `Tab`/`Enter` to expand:

### Data Types

| Prefix | Description                | Output                |
| ------ | -------------------------- | --------------------- |
| `cst`  | const variable declaration | `const name = value;` |
| `lt`   | let variable declaration   | `let name = value;`   |
| `vr`   | var variable declaration   | `var name = value;`   |
| `arr`  | array declaration          | `const name = [];`    |
| `obj`  | object declaration         | `const name = {};`    |

### Functions

| Prefix | Description                             | Output                                                   |
| ------ | --------------------------------------- | -------------------------------------------------------- |
| `ef`   | export default function declaration     | `export default function name() {}`                      |
| `efx`  | export default function JSX declaration | `export default function name() { return <div></div>; }` |
| `f`    | function declaration                    | `function name() {}`                                     |
| `fx`   | function declaration JSX                | `function name() { return <><></></>; }`                 |

### Redux

| Prefix   | Description                   | Output                                        |
| -------- | ----------------------------- | --------------------------------------------- |
| `store`  | Redux store configuration     | Redux store boilerplate                       |
| `storet` | TSX Redux store configuration | TypeScript Redux store boilerplate            |
| `slice`  | Redux slice template          | Redux slice boilerplate                       |
| `slicet` | TSX Redux slice template      | TypeScript Redux slice boilerplate            |
| `dis`    | dispatch declaration          | `const dispatch = useDispatch();`             |
| `sel`    | selector declaration          | `const value = useSelector(state => state.);` |

### Utilities

| Prefix | Description   | Output           |
| ------ | ------------- | ---------------- |
| `cl`   | console.log() | `console.log();` |

## Contributing

If you want to adapt Silly Snippets™ to your needs, feel free to:

- Modify the file containing the snippets -> `snippets/snippets.code-snippets`

## Known Issues

- Skill Issues

## FAQ

**Q: Why are some functions weirdly formatted?**

A: Why do JSX / TSX functions return an **abusive** amount of fragments? Well, I'm a **_Prettier_** enjoyer and it's made me develop OCD tendencies. I get batshit crazy when I hit that auto-format command and it removes the fragments and parentheses.

**Q: Is Silly Snippets™ going to expand to support other languages?**

A: Yes! I'm planning to work on `Bash` snippets next.

## Release Notes

### 1.0.0

Initial release of Silly Snippets™ extension with most commonly used snippet collection.

**v1.0.0 available content**  
Check [Usage](#-usage) section for complete snippet list.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

© 2025 PurrCode. All rights reserved.

**_All of this just to write undebuggable code, huh?_**
