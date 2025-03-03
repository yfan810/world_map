# Feedback and Contribution

We welcome any input, feedback, bug reports, and contributions.

All contributions, suggestions, and feedback you submitted are accepted under the [Project's license](./LICENSE.md). You represent that if you do not own copyright in the code that you have the authority to submit it under the [Project's license](./LICENSE.md). All feedback, suggestions, or contributions are not confidential. The Project abides by the [code of conduct](./CODE_OF_CONDUCT.md).

## How To Contribute Code

### Setting Up Your Environment

Fork the repository on GitHub and then clone the fork to you local
machine. For more details on forking see the [GitHub
Documentation](https://help.github.com/en/articles/fork-a-repo).

```cmd
git clone git@github.com:UBC-MDS/DSCI-532_2025_11_world_happiness.git
```

To keep your fork up to date with changes in this repo,
you can [use the fetch upstream button on GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).

Now you can install the conda environment.

```cmd
conda env create --file environment.yml
conda activate world_happiness
```

### Creating a Branch

Once your local environment is up-to-date, you can create a new git branch
which will contain your contribution
(always create a new branch instead of making changes to the main branch):

```cmd
git switch -c <your-branch-name>
```

With this branch checked-out, make the desired changes to the package.

### Creating a Pull Request

When you are happy with your changes, you can commit them to your branch by running

```cmd
git add <modified-file>
git commit -m "Some descriptive message about your change"
git push origin <your-branch-name>
```

You will then need to submit a pull request (PR) on GitHub asking to merge
your example branch into the main Altair repository. For details on creating a PR see GitHub
documentation [Creating a pull
request](https://help.github.com/en/articles/creating-a-pull-request). You can
add more details about your example in the PR such as motivation for the
example or why you thought it would be a good addition.  You will get feed back
in the PR discussion if anything needs to be changed. To make changes continue
to push commits made in your local example branch to origin and they will be
automatically shown in the PR. 

Hopefully your PR will be answered in a timely manner and your contribution will
help others in the future.

---

Made with love by GitHub. Licensed under the MIT License.