# Python CI/CD pipeline

## Linting, testing and building

The most used linters for Python as of today seem to be Pylint and Flake8. From reading a few articles it seems to be that at the moment Flake8 is more liked, because of easy setup and for having less false positive linting errors.

Python has a built-in test runner called unittest. Often developers choose to use a third-party test runner, beacuse when the number of tests become relatively high, unittest test outputs becomes quite hard to understand. A few popular third-party testing tools for Python are Robot, PyTest and Nose(2).

If and when the entire project is written in Python, for my understanding there is no need for external build tool, but some popular third-party build tools are Fabricate, Buildout and PyBuilder.

## CI alternatives

CI/CD is quite a hot topic right not so there seems to be quite a few alternatives at the moment. Interestingly many articles written about best CI/CD tools doesn't include GitHub Actions for some reason. From recently written articles the most popular choices seem to be CircleCI, GitLab, Bamboo and TeamCity. The list would be long if every tool was included.

## Setup for project

I will make the assumption that because the team working on the project is relatively small, the application is also relatively straightforward and incomplex. Assuming the team is using GitHub, then GitHub actions would be good option, because of the ease of use and minimal configuration. One thing to keep in mind though in any choise of technology e.g. Is future. If the teamsize and / or project complexity is thought of increasing significally, then maybe a more configurable self-hosted environment may be more futureproof.