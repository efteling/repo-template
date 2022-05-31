# Setup

### Create a repository from this template

1. Click the big green button `Use this template` or click <a href="../../generate">here</a>.
1. Enter a Repository name and click `Create repository from template`
1. Head over to the created repository and complete the setup.

### Complete setup

1. In the a new repository, <a href="../../edit/main/cookiecutter.json">complete the project setup</a> by editing the `cookiecutter.json` file. 
1. Hit <kbd>cmd</kbd> + <kbd>S</kbd> and then <kbd>Enter</kbd> to perform a commit (the commit message doesn't really matter).
1. Wait <a href="../../actions">Setup Repository Action</a> to complete.
1. That's it, easy isn't it?

# *{{cookiecutter.project_name}}*

[![CI](https://github.com/efteling/repo-template/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/efteling/repo-template/actions/workflows/ci.yaml)

Information about the way of working can befound here [Efteling Services Manifest](https://github.com/efteling/welcome)

This service can receive json messages concerning ticket order events, transforms them to a cannonical message and forwards them to a message broker.

The Use Cases are:

- Ticket Order Sold
- Ticket Order Cancelled
- Ticket Order Changed

## Prerequisites

.NET 6

## Instructions

Run Build

```
dotnet build *solution file* 
```

Run Tests:

```
dotnet test *solution file*
```

## Configuration
