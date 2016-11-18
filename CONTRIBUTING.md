# Contributing
This repository has master as a protected branch. __You cannot push to master.__

# Quality Guidelines
The code in this repository should be general purpose and high quality.

## Style
Code should follow [pep8](https://www.python.org/dev/peps/pep-0008/) for python code. Code for
other languages should generally follow the most accepted styles. In absence of a style guide, it
should be written to loosely conform with pep8.

## Flake8
In order to enforce code style and also halt bit rot (unused variables, unused imports, etc.) flake8
should be installed and used.

```shell
pip install flake8
flake8 ksurct
```

## Documentation
Documentation should be written for future members.

Prefer active documentation to passive documentation. Active documentation means using doc
strings instead of comments so that the documentation generators can use it. Using assert statements
instead of comments to describe the api. Using doc tests for examples if possible. Using convention
instead of commented code. Using github issues to describe new features. Python comments should be
used sparingly to explain code that looks incorrect or is confusing.

Type annotations may be used as shown in [pep484](https://www.python.org/dev/peps/pep-0484/). This
is a recent-ish development in the python community, so if it becomes a problem, we will abandon
type annotations.

# Branching
## Branch Names
Branch names should be descriptive of the contribution and may contain a leading number that
corresponds to the issue number.

## Pull Requests
Code should enter master only through pull requests. A pull request should be reviewed by at least
two people, of which the requester can be one and one must be a senior club developer.
