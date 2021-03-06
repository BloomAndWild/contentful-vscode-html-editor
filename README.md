# VSCode 'Monaco' Editor UI Extension for contentful
This UI extension for contentful allows the use of the excellent 'Monaco' editor (From VSCode) in their content types.

## Example:
![screen shot 2018-05-30 at 18 10 39](https://user-images.githubusercontent.com/1135454/40737318-411af474-6438-11e8-8952-bf1ff0f1ee96.png)

## Installation into Contentful

### 1) Setup the hosting via GitHub Pages
1) Clone / Fork this repo
2) If forked, under GitHub, go to Repo Settings -> "GitHub Pages"
3) Set to "Source" as "Master Branch Folder"

### 2) Setup the Extension
1) In contentful, go to "Space Settings" -> "Extensions"
2) Click "Add Extension" (Top right), then "Add a new extension"
3) Enter the following:
- Name: Choose whatever you want (We went with VS Code Monaco)
- Field Types: Text
- Self Hosted URL: `https://{name}.github.io/{repo-name}/`

### 3) Change the content model
1) Go to "Content Model", choose a content model
2) Click "Settings" under the field, then go to the "Appearance" tab
3) Select the "VS Code Monaco" (or the name you set in step 2 above)
4) Enjoy!

### Development
1) Go to repo - then run `python -m SimpleHTTPServer 8000` to start a simple http server