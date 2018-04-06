# GitFlow

This is a collection of best practices of [Frannca's](https://github.com/Frannca/frannca) projects maintenance.

## Table of Contents

- [Motivation](#motivation)
- [First Steps](#firststeps)

## Motivation

There are so many great **Open Source** projects that is helping our company to grow that would be fair to start to 
share some projects as well. This year we decided to start to Open Source some of our projects on **GitHub**. 
Starting with our [website](http://frannca.com) and now by creating some **Angular** libraries. See our 
[Projects](#projects).


## First Steps

1. [Commit Message Guidelines](#commitmessageguidelines)

### Commit Message Guidelines

We use the [Angular Commit Message Guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#commits) 
and to follow this guidelines, there is a great CLI wizard: [Commitizen](https://github.com/commitizen/cz-cli).

**Commitizen installation**

```
npm install -g commitizen
```

**Making the repository Commitizen-friendly**

```
commitizen init cz-conventional-changelog --save-dev --save-exact
```

If the project does not has the `package.json` file, the Commitizen CLI can not be installed. Create the file by 
running `npm init`.

For more detailed information, check the Commitizen repository.
