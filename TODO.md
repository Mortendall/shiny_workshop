Review the [template
guide](https://template-workshop.rostools.org/docs/guide/next-steps) for more
information on how to use the template and the next steps after copying the
project.

Next, run these commands in the terminal while inside of the project's
directory. Either use your system's terminal or use the built-in terminal in VS
Code, Positron, or RStudio:

- `git init -b main` to create the project as a Git repository.
- `just install-dev-deps` to install development tools.
- `just list-todos` and complete all the TODO items.
- `just build-readme` to build the Markdown version of the README.

After going through all the TODO items and doing these tasks, add and commit the
files into the Git history.To get the repository up on GitHub use the [gh CLI](https://cli.github.com/) to
create the GitHub repository from the terminal with:

```
gh repo create mortendall/shiny_workshop --source=. --public --push
```



If you will be using GitHub pages, run `quarto publish gh-pages` to setup and
start publishing the website to GitHub Pages.

Finally, some optional tasks:

- `just install-precommit` to install the pre-commit hooks.
- If relevant, connect [GoatCounter](https://www.goatcounter.com/).
- If relevant, connect [pre-commit.ci](https://pre-commit.ci/) to the repository
  and enable the pre-commit hooks.
