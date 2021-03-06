> ### Notice
> This package and repository is no longer being maintained. Feel free, as always, to fork and make your own versions!
> My apologies for having to close down this project; I simply don't have enough time anymore to keep track of all the API changes in Brackets required to keep this working.
>
> For an alternative minifier based off this one, take a look at [@abagshaw's fork](https://github.com/abagshaw/brackets-minifier)

# Minifier for [Brackets](https://github.com/adobe/brackets)

*Minifies JavaScript and CSS files in Brackets and saves to `{filename}.min.{ext}` using UglifyJS2 (for JavaScript) and YUI (for CSS).*

## Installation

1. Run Brackets
2. Select *File > Install Extension...*
3. Enter `https://github.com/alfredxing/brackets-minifier/archive/master.zip` as Extension URL.
3. Click Install to begin downloading and installing the extension.

#### Alternative method
Clone this repository into `~/Library/Application Support/Brackets/extensions/user/` and restart Brackets.

## Usage
To minify a file, use the keyboard shortcut `Cmd/Ctrl+M`. You can also minify files on save by checking the corresponding item in the *Edit* menu.
