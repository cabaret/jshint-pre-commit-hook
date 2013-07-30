# JSHint Git Pre-commit Hook

## Description

Git pre-commit hook to run JavaScript files through JSHint before committing. If it fails, you will not be able to commit.


## Installation

- Install JSHint through NPM: `npm install -g jshint`
- Place this file in `/yourproject/.git/hooks/`
- `chmod +x pre-commit`


## Bypass

- You can bypass the hook by using the 'no-verify' option: `git commit --no-verify -m "my message"` or `git commit -nm "my message"`
- This is useful in the case of committing third-party libraries.


## JSHint options

- Include a .jshintrc file in your project to specify options. For more information, visit the [JSHint docs](http://www.jshint.com/docs/config/).


----
Joris Ooms - 2013
