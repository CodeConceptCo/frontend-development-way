## 3. Git hooks

Git hooks are scripts that Git executes before or after events such as commit, push, and receive.

For example, you can run test and linter on the **pre-commit **event and commit will not be created until all of them are finish successfully. Or send slack notification about this commit on **post-commit**.



All list of event and description can be found here https://git-scm.com/docs/githooks



For the NPM integration use husky library https://github.com/typicode/husky