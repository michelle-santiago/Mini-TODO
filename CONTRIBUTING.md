# Contributing

<img src="https://blog.tooljet.com/content/images/size/w2000/2022/09/Screenshot-2022-09-27-at-08.03.21.png"/>

Hi there! We are small team thrilled that you'd like to contribute to our projects under Hacktoberfest.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [project's open source license](LICENSE).

## Opening an issue

Thank you for taking the time to open an issue, your feedback helps make Hacktoberfest better.
Before opening an issue, please be sure that your issue hasn't already been asked by using [GitHub search](https://help.github.com/articles/searching-issues/)

Here are a few things that will help us help resolve your issues:

- A descriptive title that gives an idea of what your issue refers to
- A thorough description of the issue, (one word descriptions are very hard to understand)
- Screenshots (if appropriate)
- Links (if appropriate)

## Submitting a pull request

1. Clone the repository
2. Configure and install the dependencies: (See the [README](README.md) for more details)
3. Create a new branch: `git checkout -b my-branch-name`
4. Make your changes, push to your branch and submit a pull request.
5. Wait for your pull request to be reviewed and merged!

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, consider submitting them as separate pull requests.
- Write a [good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

## Formatting and styling

This repository follows formatting and styling rules defined in `.eslintrc` and `.prettierrc` files and are applied via the Prettier and ESLint packages. Please make sure that your changes are linted before opening pull requests to this repository.

### Linting setup

1. Make sure [Node.js](https://nodejs.org/en/download/) is installed on your machine.
2. In the root directory run `npm install` to install all dependencies.

#### VSCode

If you are using VSCode, the official [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) extensions allow for automatic linting and formatting in the editor.

#### CLI commands

1. Run `./node_modules/.bin/eslint .` to check for linting errors.
2. Run `./node_modules/.bin/eslint --fix .` to attempt fixing issues automatically.
3. Run `npx prettier --check .` to check for formatting errors.
4. Run `npx prettier --write .` to automatically format all files in the directory.

## Resources

- [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)
- [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
- [GitHub Help](https://help.github.com)
