# Overtio — join open software
## Script store
Place where end user user can find solutions for his problems I terminal.
Users often see that they cannot do something because of some shit. Now you can post solution on our platform and user will simply need to go and click apply. And we will check that commands are not hazardous for him. 

Good example of a script for such store:
[Converting Image File Formats with the Command Line & sips  |   OSXDaily](https://osxdaily.com/2013/01/11/converting-image-file-formats-with-the-command-line-sips/)

- Libre/Open Software

```
for i in [filename]; 
do sips -s format [image type] $i --out [destination]/$i.[extension];done
```

Market for open source software solutions
Like bottle nose


## Tavern - independent App Store
- Start with making a cli app where you can see categories of casks and some kind of comments, etc.

### Features
- Download apps
- Delete apps
- Safe settings for all the apps (maybe)
- Easy to upload, app will create the tap for brew and upload your app
- Add ability to install cli apps from PyPi

### Technology
- brew at the backend
- macports at the backend as well (future)

### GUI apps
- MacVim
- Sublime
- VSCodium

### CLI apps
- Brew
- Exa (make it possible to change aliases in the app)
- Trash

### Snips - Small Shell commands
Little app with scripts, you can add the script there and give it a name and use it as a button.

- Find files with "run-time" in name
 `grep --include=\*-out.json -ilRe "run-time" .`
- Find all files with integers in name
 `grep --include=\*-out.json -ilRe "\d"`

### Fonts
- Fira code

#dev/apps
