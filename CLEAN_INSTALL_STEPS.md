# Link Sublime settings to Dropbox shared folder;

* Close Sublime

Run

```
DSTPATH="$HOME/Library/Application Support/Sublime Text 3"
DROPBOX_PATH="$HOME/Dropbox/Shared Folders/Software/Sublime"
rm -rf "$DSTPATH/Installed Packages"
rm -rf "$DSTPATH/Packages"
mkdir -p "$DSTPATH"
ln -s "$DROPBOX_PATH/Packages" "$DSTPATH/Packages"
ln -s "$DROPBOX_PATH/Installed Packages" "$DSTPATH/Installed Packages"
```

