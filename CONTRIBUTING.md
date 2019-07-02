# Contributing to React to Framer

This guide was basically copy and pasted from the beloved people at [CodeSandbox](https://codesandbox.io)

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Setting Up the project locally](#setting-up-the-project-locally)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Available scripts in your local environment](#available-scripts-in-your-local-environment)

## Code of Conduct

We have a code of conduct you can find [here](https://github.com/fivenp/react-to-framer/blob/master/CODE_OF_CONDUCT.md) and every contributor is expected to obey the rules therein. Any issues or PRs that don't abide by the code of conduct may be closed.

## Setting Up the project locally

**Working on your first Pull Request?** You can learn how from this _free_ series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

To install the project you need to have `yarn` and `node`

1.  [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your fork:

    ```
    # Clone your fork
    git clone https://github.com/<your-username>/react-to-framer.git

    # Navigate to the newly cloned directory
    cd react-to-framer
    ```

2.  `yarn` to install dependencies
3.  `yarn TBD`

> Tip: Keep your `master` branch pointing at the original repository and make
> pull requests from branches on your fork. To do this, run:
>
> ```
> git remote add upstream https://github.com/fivenp/react-to-framer.git
> git fetch upstream
> git branch --set-upstream-to=upstream/master master
> ```
>
> This will add the original repository as a "remote" called "upstream,"
> then fetch the git information from that remote, then set your local `master`
> branch to use the upstream master branch whenever you run `git pull`.
> Then you can make all of your pull request branches based on this `master`
> branch. Whenever you want to update your version of `master`, do a regular
> `git pull`.

## Submitting a Pull Request

Please go through existing issues and pull requests to check if somebody else is already working on it, we use `WIP` label to mark such issues.

Also, make sure to run the tests and lint the code before you commit your changes.

```
yarn test
yarn lint
```

Thank you for taking the time to contribute! :+1:

## Available scripts in your local environment

In the project directory, you can run:

TBD....
