# Development guidelines

## Principles
* We use **git** for versioning our projects
	- we love frequent commits
	- we love commits with expressive messages
* We follow **[semver.org](https://semver.org)** for named versions and our release cycle semantics
	- we love stable software
	- we love high quality by multiple assessor principle
* We use **git-flow** with standard settings for better, collaborative team-development and stricter rules how to contribute to stable stages of the project
	- we integrate batches of commits as features
	- we focus on feature-development and separate responsibility of development, testing and integration
* We use **github issues** for issue tracking
	- we love constructive criticism for self-improvement
	- we love to communicate our progress
* We use **Intellij IDEA** and other JetBrains IDEs for easier code-development
	- we rely on strong shoulders
	- we accept counsel of other experts
	- we avoid reinventing the wheel



# <a name="links"></a>Link collection #
## Use git flow ##
* http://danielkummer.github.io/git-flow-cheatsheet/
* https://www.atlassian.com/git/workflows#!workflow-gitflow
* http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/
You should remember to push /develop-branch to origin develop!

## Designing REST with symfony ##
* https://github.com/FriendsOfSymfony
* http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/

## REST security ##
We will go the simple and well secured approach: force https and serve api tokens to track and decouple user devices.

* http://www.thebuzzmedia.com/designing-a-secure-rest-api-without-oauth-authentication/
* https://stormpath.com/blog/secure-your-rest-api-right-way/
