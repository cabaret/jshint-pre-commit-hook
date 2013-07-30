# JSHint Git Pre-commit Hook

- Install JSHint through NPM: `npm install -g jshint`
- Place this file in /yourproject/.git/hooks/
- Upon committing a JavaScript file, this hook will run the file through JSHint. If it fails, you will not be able to commit.

----

- You can bypass the hook by using the 'no-verify' option: `git commit --no-verify -m "my message"` or `git commit -nm "my message"`
  This is useful in the case of committing third-party libraries.

----

- Include a .jshintrc file in your project to specify options. For more information, visit the [JSHint docs](http://www.jshint.com/docs/config/).