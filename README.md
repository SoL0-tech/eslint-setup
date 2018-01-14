# Linter-enforced Code Style for JS and Typescript

Simple rule-based linting for ESLint. I've set this up with rules that I believe should be enforced for JS development, but you're welcome to modify it to your taste.

## Usage

1. Copy the ```.eslintrc.json``` file into your project's root directory.
2. Install ESLint and the necessary plugins: ```npm install -g eslint eslint-plugin-import```.
3. Configure your editor or pre-build scripts to lint your code.
    I use VS-Code with the ```ESLint``` extension and the following lines in the user configuration file:
    ```
    "files.trimTrailingWhitespace": true,
    "files.insertFinalNewline": true,

    "eslint.packageManager": "yarn",
    "eslint.run": "onType"
    ```

Enjoy!
