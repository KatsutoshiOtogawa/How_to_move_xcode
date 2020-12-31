# How to move xcode and switch place

xcode.app is huge.

```shell
# check your xcode install path.
xcode-select --print-path

# move xcode 
# ex) you move to /Volumes/External_HDD/App this path is 
sudo mv /Applications/Xcode.app /Volumes/EXTERNAL_HDD/App/

# switch xcode location to you want to use path
xcode-select --switch /Volumes/External_HDD/App/Xcode.app

# check your xcode install path again.
xcode-select --print-path
```
