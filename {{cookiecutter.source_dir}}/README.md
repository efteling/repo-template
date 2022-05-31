# *{{cookiecutter.solution_name}}*

[![CI](actions/workflows/ci.yaml/badge.svg?branch=main)](actions/workflows/ci.yaml)

Information about the way of working can befound here [Efteling Services Manifest](https://github.com/efteling/welcome)

This service can receive json messages concerning ticket order events, transforms them to a cannonical message and forwards them to a message broker.
## Features
The Use Cases are:

- Ticket Order Sold
- Ticket Order Cancelled
- Ticket Order Changed

## Requirements

.NET 6

## Installation

## Usage
[API definition](API.MD)

## Instructions

Run Build

```
dotnet build {{cookiecutter.solution_name}}.sln 
```

Run Tests:

```
dotnet test {{cookiecutter.solution_name}}.sln
```

## Configuration
