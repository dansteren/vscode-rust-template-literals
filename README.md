# vscode-rust-template-literals

Syntax highlighting for code like:

```js
const helloWorld = rust`
  fn main() {
    println!("Hello World!");
  }
`;
```

## Usage

This package is not currently published to the marketplace. Instead you will need to package and install the extension manually.

```shell
npx vsce package
```

This will generate a vscode-rust-template-literals-0.1.0.vsix file. You can then [install the vsix file](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix):

```shell
code --install-extension vscode-rust-template-literals-0.1.0.vsix
```
