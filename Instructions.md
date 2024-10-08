# How to create a file using the Terminal - macOS
![Terminal on Macbook](https://help.apple.com/assets/63FFD63D71728623E706DB4F/63FFD63E71728623E706DB56/en_US/4e8328e6927032645dfb715a76f5a527.png)
### 1. Open Terminal Application

- On macOS: Open *Spotlight* by pressing the *'Command + Spacebar'* buttons on your keyboard, then type "Terminal" and open the application by pressing the *'Enter'* key.

### 2. Go to Specific Directory where the file should live 
- To access the specific directory, use the **cd** command to enter the directory where want to create the file.

_For example:_
```javascript
~cd/code/ga/labs/intro-to-markdown-lab
```

### 3. Creating your new file 
- To create a new file, you can use the **touch** command to create a new file within your desired directory. 

_For example:_
```javascript
touch index.html
```

*Example for creating multiple new files at once:*
```javascript
touch README.md Instructions.md index.html app.js
```
When creating multiple files we name them one after another making sure to seperate them with a space -- without additional code or symbols.

### 4. Checking that the file exists

- To check whether or not the file you created exists within your Terminal, use the ***ls** command. 

_For example:_
```javascript
Intro-to-markdown-lab git(main) ls
README.md Instructions.md index.html app.js
```
For more information on the terminal and munipulating files, check out this [MDN Web docs page.](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line)