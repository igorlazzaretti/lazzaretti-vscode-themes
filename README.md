# My VsCode Themes in Marketplace 
<div align="center">
  <br>

</div>

## Quem Sou eu?

Estagiário na Plenatech!

## How to

- Star coding:

npm install -g yo generator-code

- Then:

yo code

- Add Publisher in package.json after Description in the begining of the code.

"publisher": "YourNameinMarkeplaceHere"

- Add your json theme files in \themes 

- In package.json update the path
 
 "contributes": {
    "themes": [ 

- run for publish your theme:

npm install -g @vscode/vsce

- run

vsce package

- send the generated file in your acount here https://marketplace.visualstudio.com/ 

- And that's it! Bye