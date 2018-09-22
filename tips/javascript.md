# JavaScript

Here you'll find some tips on exploring a JavaScript codebase.

## Node

After cloning the repo and installing the dependencies, there are several things you can do:

* If it's an application, try to run it. It may be as simple as doing `npm start` or it may need a build step. Anyway, try to figure it out.
* If it's a library, you can run [`npm link`](https://docs.npmjs.com/cli/link) to use it from another directory. This is how it works:
  - Run `npm link` in the project directory
  - Go to another directory and run `npm link <project-name>`
  - Now if you do `require('<project-name>')` in that directory, the local package will be used. If you modify it, the changes will be available immediately (unless there's a build step involved, in which case you may use a watch+build script, if there is one).
* Use [`ndb`](https://github.com/GoogleChromeLabs/ndb) to inspect it.
* Look at the `main` and `scripts` properties in the `package.json`.
* Use the node `repl`: open it and do `package = require('.')` and you will be able to experiment with the module.

## Web

* As in node, try to use it (in this case, in your browser). Use the devtools to inspect it.
* Try to use a non-minified version; if that's not possible, at least make sure that you are including the sourcemaps.
* Use an online editor like [`CodeSandbox`](https://codesandbox.io/) to experiment with changes.
