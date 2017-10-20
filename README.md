# memo

## Fork
```
git clone https://github.com/YOUR-USERNAME/FORKED-REPO
git remote add upstream https://github.com/ORIGINAL-USERNAME/REPO
```

## Syncing Fork
```
git fetch upstream
git checkout master
git merge upstream/master
```

## Terminal Keyboard shortcuts

### Moving Cursor
```
Ctrl+A:  Go to the beginning of the line
Ctrl+E:  Go to the end of the line
Alt+B:   Go back one word
Ctrl+B:  Go back one character
Alt+F:   Go forward one word
Ctrl+F:  Go forward one character
Ctrl+XX: Move between the beginning of the line and the current position of the cursor
```

### Deleting Text
```
Ctrl+D: Delete the character under the cursor
Alt+D:  Delete all characters after the cursor on the current line
Ctrl+H: Delete the character before the cursor
``` 

### Cut & Paste
```
Ctrl+W: Cut the word before the cursor
Ctrl+K: Cut the part of the line after the cursor
Ctrl+U: Cut the part of the line before the cursor
Ctrl+Y: Paste
```

### Capitalize
```
Alt+U: Capitalize every character from the cursor to the end of the current word.
Alt+L: Uncapitalize every character from the cursor to the end of the current word.
```

## Securely Delete Data
```
shred -vfzu -n 10 file
srm -vr /dir
```
