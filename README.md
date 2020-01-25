# Continuous Integration with GitHub Actions

## Purpose

This repository is a personal collection of useful actions tailored to my personal preferences. These actions are grouped into five stages:

1. lint
2. build
3. quality
4. test
5. deploy

As GitHub actions does not support stages like GitLab, the `jobs.<job_id>.needs` keyword is used. Reference: [Workflow syntax for GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#jobsjob_idneeds)

## Standard CI

Consider Print default variables for debugging

## References

* [Publishing Actions in Github Marketplace](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/publishing-actions-in-github-marketplace)
* [Workflow syntax for GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#jobsjob_idneeds)
