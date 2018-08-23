## 1. Code Style

It’s important to keep all code consistent and clear across all project, even if you work in a team. The easiest way to do this is to use [TSlint](https://palantir.github.io/tslint/) for typescript or [ESlint](https://eslint.org/) for JavaScript in combination with [Prettier](https://github.com/prettier/prettier). Prettier is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

You can define your own config our use existing like [AirBnB js style guide](https://github.com/airbnb/javascript). 

If you use [VC Code](https://code.visualstudio.com) you can setup auto-formatting on file saving with Prettier extensions and an option in settings `"editor.formatOnSave": true`.