
## Install

### Latest version from GitHub

```
cordova plugin add https://github.com/tessarini/cordova-plugin-new-entry-to-plist.git
```

## Usage
Set the attribute ans its value, inside the  `plugin.xml`. For example:

```
<dict>
    <key>ITSAppUsesNonExemptEncryption</key>
    <false/>
</dict>
```
For the changes to `plugin.xml` to take effect, you must refresh the `ios.json` file (inside the `/plugin` folder):
```
$ cordova platform rm ios
$ cordova platform add ios
```

## License

[MIT License](http://ilee.mit-license.org)
