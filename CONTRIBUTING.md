# Contributing to Akron Code Club Open Source

You want to contribute? Thank you! Akron Code Club Open Source is the work of [many contributors](https://github.com/AkronCodeClub/intro-to-open-source/graphs/contributors). You're encouraged to submit [pull requests](https://github.com/AkronCodeClub/intro-to-open-source/pulls), [propose features and discuss issues](https://github.com/AkronCodeClub/intro-to-open-source/issues).

#### Find Something to Work on

If you want to contribute but aren't sure what to work on, we keep our list of current todos on our [issues page](https://github.com/AkronCodeClub/intro-to-open-source/issues).

#### Fork the Project

Fork the [project on GitHub](https://github.com/AkronCodeClub/intro-to-open-source) and check out your copy.

```
git clone https://github.com/contributor/intro-to-open-source.git
cd intro-to-open-source
git remote add upstream https://github.com/AkronCodeClub/intro-to-open-source.git
```

#### Create a Topic Branch

Make sure your fork is up-to-date and create a topic branch for your feature or bug fix.

```
git checkout master
git pull upstream master
git checkout -b my-feature-branch
```

#### Install Dependencies, Build, and Test

Ensure that you can build the project and run tests.

#### Write Tests

Try to write a test that reproduces the problem you're trying to fix or describes a feature that you want to build.

We definitely appreciate pull requests that highlight or reproduce a problem, even without a fix.

#### Write Code

Implement your feature or bug fix.

Make sure that your code builds without errors.

#### Write Documentation

Document any external behavior in the [README](README.md).

#### Commit Changes

Make sure git knows your name and email address:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Writing good commit logs is important. A commit log should describe what changed and why.

```
git add ...
git commit
```

#### Push

```
git push origin my-feature-branch
```

#### Make a Pull Request

Go to https://github.com/contributor/intro-to-open-source and select your feature branch. Click the 'Pull Request' button and fill out the form. Pull requests are usually reviewed within a few days.

#### Rebase

If you've been working on a change for a while, rebase with upstream/master.

```
git fetch upstream
git rebase upstream/master
git push origin my-feature-branch -f
```

#### Update CHANGELOG Again

Update the [CHANGELOG](CHANGELOG.md) with a description of what you have changed.

Amend your previous commit and force push the changes.

```
git commit --amend
git push origin my-feature-branch -f
```

#### Check on Your Pull Request

Go back to your pull request after a few minutes and see whether it passed muster with Travis-CI and AppVeyor. Everything should look green, otherwise fix issues and amend your commit as described above.

#### Thank You

Please do know that we really appreciate and value your time and work. We love you, really.
