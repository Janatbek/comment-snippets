# Comment-snippets for Visual Studio Code
Typescript and JavaScript comment and debug helper snippets,

### console.log('');
Type ```log``` and hit ```tab``` key and you will have ```console.log('|'); ``` placeholder.

### debugger;
Type ```d``` and hit ```tab```key  and you will have ```debugger; ``` entered in your code.


### Multi-line comment with placeholder and divider
Type ```com``` and hit ```tab```key  and you will have 
```
/**
* -------------------------------------------------- *
* | *
* -------------------------------------------------- *
*/ 
``` 
multi-line comment with divider header and footer in your code.
#### Notes
I removed trailing white spaces for tslint and jslint;
for ```debugger;``` typescript can raise an error, but you can disable ts-lint for debugger temporary.
