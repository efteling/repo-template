# *[Replace]Service description*

[![CI](https://github.com/efteling/repo-template/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/efteling/repo-template/actions/workflows/ci.yaml)

[Efteling Services Manifest](https://github.com/efteling/welcome)

This service can receive json messages concerning entrance ticket event, transforms them to a cannonical message and forwards it to a message broker.

The Use Cases are:

- Sold entrance ticket
- Cancelled entrance ticket
- Changed entrance ticket 

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
