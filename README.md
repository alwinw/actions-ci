# Continuous Integration with GitHub Actions

## Purpose

This repository is a personal collection of useful actions tailored to my personal preferences. These actions are grouped into five stages:

1. lint
2. build
3. quality
4. test
5. deploy

As GitHub actions does not support stages like GitLab, the `jobs.<job_id>.needs` keyword is used. Reference: [Workflow syntax for GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#jobsjob_idneeds)

Icons are from [Feather](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/metadata-syntax-for-github-actions#icon).

## Features

1. lint
    - [python](https://github.com/AlwinW/actions-lint-python)
        - black, pycodestyle, flake8, pylint, isort, mypy
        - Will autoformat and use git diff to show results
2. build
3. quality
    * [bandit](https://github.com/PyCQA/bandit)
4. test
5. deploy

## Standard CI

Consider Print default variables for debugging

## References

* [Publishing Actions in Github Marketplace](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/publishing-actions-in-github-marketplace)
* [Workflow syntax for GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions)
