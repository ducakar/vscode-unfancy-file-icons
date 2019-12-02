# Unfancy icons

A file icon theme for Visual Studio code.
Based on [atom-unfancy-file-icons][atom-extension] package.

## Rules

- Use only icons from Octicons (shipped with Atom)
- Use a simple color code (with a few exceptions when it make more sense,
  like for ruby files) which works as follow:
  - green for source files
  - yellow for template and stylesheet files
  - cyan for documentation files (markdown, latex, pdf, etc.)
  - blue for media files (images, videos, art software files, etc.)
  - violet for data files (json, yml, csv, etc.)
  - magenta for configuration files (.gitignore, .ruby-version, etc.) and scripts
- Use generic icons rather than trying to find one for each file extension
  (except when an icon in Octicons fit the file, like with ruby files)

## Screenshot

![Screenshot][screenshot]

[atom-extension]: https://github.com/abe33/atom-unfancy-file-icons
[screenshot]: https://raw.githubusercontent.com/alexesprit/vscode-unfancy-file-icons/master/media/screenshot.png
