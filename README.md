# babel-review
Quick babel setup

## Steps taken
- `npm init` to create "package.json"
- `npm install --save-dev babel-cli babel-preset-env` to install CLI interface for Babel and Babel preset package which contains configuration for most recent ECMAScript features supported by Babel
- "src" folder created with "index.js" file
- "build" command added in field "scripts" to "package.json" for running Babel locally in project and output "index.js" from "src" to "lib"
> Babel is now configured but it isn't doing anything
- create ".babelrc" file in the root directory
- add this lines in ".babelrc" file: `
    {
        "presets": ["env"]
    }
`

