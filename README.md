# all_notes

# Zsh
```nano ~/.zshrc```
Save and Exit:
If you're using Nano, press Ctrl+O to save, then press Enter, and finally press Ctrl+X to exit.
Apply Changes:
```source ~/.zshrc```

# Xcode_iOS
``` sudo sh -c 'xcode-select -s /Applications/Xcode.app/Contents/Developer && xcodebuild -runFirstLaunch' ``` 
``` sudo xcode-select --install ```
``` sudo xcodebuild -license accept ```

# Add Flutter

``` export PATH="/Users/thawdezin/Flutter/flutter/bin:$PATH" ```

## Upgrade Flutter
``` flutter pub upgrade --major-versions ```

## Get CLI
``` dart pub global deactivate get_cli ```
``` dart pub global activate -s git https://github.com/knottx/get_cli.git ```
``` flutter pub global activate get_cli 1.8.0 ```

## Gradle <-> Kotlin <-> Java
``` https://docs.gradle.org/current/userguide/compatibility.html ```

## VScode formatter
``` Shift + Alt + F ``` for Windows 
``` Shift + Options + F ``` for Mac
``` Ctrl + Shift + I ``` for Linux

## Useful Shortcuts

Cmd + Shift + 4 -> screenshot
Cmd + Shift + O -> Xcode file search
Cmd + Ctrl + q -> Lock macbook
Cmd + Shift + F -> Android Studio All Search (same for Xcode)

### Get SHA1 for Firebase
``` ./gradlew signingReport ```

## Flask
``` python3 -m flask run --host=0.0.0.0 ```

## Python

```
python3 -m venv hsumyat
source hsumyat/bin/activate (macOS)
.\hsumyat\Scripts\activate (windows)
```

## to do to Change Laptop

1. ``` firebase logout ```
2. ``` git config --global --unset-all ```
3. ``` git credential reject ```
4. ``` gh auth logout ```
5. Logout all google accounts (Firefox, Safari, Chrome)
6. Uninstall all browsers or reset them all
7. Delete Server login password in Key Chain Acces -> smb://10.95.101.31
8. Delete Android Studio and .jks files
9. Delete Python Environment > source $HOME/tdz/hsumyat/bin/activate


## Github

https://raw.githubusercontent.com/thawdezin/
