# Setup

### Create a repository from this template

1. Click the big green button `Use this template` or click <a href="../../generate">here</a>.
1. Enter a Repository name and click `Create repository from template`
1. Head over to the created repository and complete the setup.

### Complete setup

1. In the new repository add a secret named '**REPO_SETUP_TOKEN**'. Set this to a value of a Personal access token with the scope '**workflow**'
1. In the new repository, <a href="../../edit/main/cookiecutter.json">complete the project setup</a> by editing the `cookiecutter.json` file. 
1. Hit <kbd>cmd</kbd> + <kbd>S</kbd> and then <kbd>Enter</kbd> to perform a commit (the commit message doesn't really matter).
1. Wait <a href="../../actions">Setup Repository Action</a> to complete.

---
# What is this all about?

On June 6, 2019, [GitHub introduced Repository Templates](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) giving users an easy way to share boilerplate for their projects. Stefan Buck created a cookciecutter script that replace some tokens so creating a new repo gets that much easier. [Read the full blog post](https://stefanbuck.com/blog/repository-templates-meets-github-actions) to learn how to template new projects using repository templates and GitHub Actions.