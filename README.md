# GitFlow

This is a collection of best practices of [Frannca's](https://github.com/Frannca/frannca) projects maintenance on 
GitHub.

## Table of Contents

- [Motivation](#motivation)
- [First Steps](#first-steps)

## Motivation

There are so many great **Open Source** projects that is helping our company to grow that would be fair to start to 
share some projects as well. This year we decided to start to Open Source some of our projects on **GitHub**. 
Starting with our [website](http://frannca.com) and now by creating some **Angular** libraries. See our 
[Projects](#projects).


## First Steps

1. [Commit Message Guidelines](#commit-message-guidelines)
2. [Recommended Community Standards](#recommended-community-standards)

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

### Recommended Community Standards

The GitHub has a checklist with some important things that your project must have. It is important to follow this 
standards to reach out a good quality project, and to helo others to help you by submitting pull requests.

- **Description**
  - Add a description for your project, it is very important because of this description the people can find your project 
easily.
- **README**
  - The first thing that anyone sees when enters your project is the README. It is very important to create a good README. 
We are going to see more details in the next topics. 
- **Code of conduct**
  - GitHub provides two templates, but we mainly use the first one: Contributor Covenant.
- **Contributing**
  - If you want to people to contribute to your project, you must have a contributing file. This file contains the 
guidelines to anyone that wants to report bugs and create pull request.
- **Licence**
  - We always use the MIT License in all the projects on GitHub.

**Issues or pull request templates**

Create this files save time and creates a standard to anyone that wants to open an issue or create a pull request.
