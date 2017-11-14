# Comment-snippets for Visual Studio Code
Typescript and JavaScript comment and debug helper snippets,
You can define your own snippets for specific languages. To open up a snippet file for editing, open User Snippets under File > Preferences (Code > Preferences on Mac) and select the language for which the snippets should appear.
Snippets are defined in a JSON format and stored in a per user (languageId).json file. For example, JavaScript and Typescript snippets go in a javascript.json and typescript.json files.

[read more about Creating your own Snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

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
