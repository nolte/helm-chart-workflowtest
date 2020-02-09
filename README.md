# Helm Chart Test Project 

This is a Test project for Develop a GitHub Workflow based, release and deployment process.

## Features

* Update version in metadata files like readme like (0.97.0).
* Create a Github Relase and Tag.
* Mark Develop Versions with a ```x.y.z-dev``` sufix.
* Generate a Release Changelog used [spring-io/github-release-notes-generator](https://github.com/spring-io/github-release-notes-generator) 
* Use [Issue-Label-Bot](https://github.com/machine-learning-apps/Issue-Label-Bot) for labeling.
* Use [banyan/auto-label](https://github.com/banyan/auto-label) for adding labels by commited content.

## Helm Specific Feature

* Deploy the Release to [nolte/helm-charts](https://github.com/nolte/helm-charts), a GitHub based [Chart Repository](https://helm.sh/docs/topics/chart_repository/).
