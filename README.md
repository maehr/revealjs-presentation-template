# GitHub template for small projects

This GitHub template is agnostic to the programming language used, uses GitHub Actions to manage issues and pull requests, and helps enforce best practices for small projects.  To use the template, [generate](https://github.com/maehr/github-template/generate) a new project and perform the following tasks.

* [x] add `Moritz Maehr`, `maehr` and `academic-revealjs-template` to [README.md](README.md) and change it according to [www.makeareadme.com](https://www.makeareadme.com/)
* [x] add `2019` and `Moritz Maehr` to [LICENSE.md](LICENSE.md)
* [x] add `moritz.maehr@gmail.com` to [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
* [x] use [www.gitignore.io](https://www.gitignore.io/) to enhance [.gitignore](.gitignore)
* [x] use [gitattributes.io](https://gitattributes.io/) to enhance [.gitattributes](.gitattributes)
* [x] add secrets variables to [secrets.example.env](secrets.example.env)
* [ ] add [GitHub actions](https://help.github.com/en/articles/workflow-syntax-for-github-actions) in `.github/workflows/` according to [starter-workflows](https://github.com/actions/starter-workflows)
* [ ] add documentation to [docs](docs/index.md) and activate [gh-pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages)
* [x] [protect](https://help.github.com/en/articles/configuring-protected-branches) the master branch to enforce a [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow
* [x] activate [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/) and change [SECURITY.md](SECURITY.md) accordingly

* https://html5boilerplate.com/
* https://github.com/gnab/remark/wiki/Using-with-Jekyll

* https://github.com/edwardtufte/tufte-css
* alternatively https://github.com/matejlatin/Gutenberg
* https://dev.to/emmawedekind/how-to-build-a-captivating-presentation-using-html-css--javascript-nno
---

# academic-revealjs-template

Foobar is a Python library for dealing with word pluralization.

[![GitHub issues](https://img.shields.io/github/issues/maehr/academic-revealjs-template.svg)](https://github.com/maehr/academic-revealjs-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/academic-revealjs-template.svg)](https://github.com/maehr/academic-revealjs-template/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/academic-revealjs-template.svg)](https://github.com/maehr/academic-revealjs-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/maehr/academic-revealjs-template.svg)](https://github.com/maehr/academic-revealjs-template/blob/master/LICENSE.md)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Support

This project is maintained by [@maehr](https://github.com/maehr). Please understand that we won't be able to provide individual support via email. We also believe that help is much more valuable if it's shared publicly, so that more people can benefit from it.

| Type                   | Platforms                                                    |
| ---------------------- | ------------------------------------------------------------ |
| 🚨 **Bug Reports**      | [GitHub Issue Tracker](https://github.com/maehr/academic-revealjs-template/issues) |
| 🎁 **Feature Requests** | [GitHub Issue Tracker](https://github.com/maehr/academic-revealjs-template/issues) |

## Roadmap

No changes are currently planned.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/maehr/academic-revealjs-template/tags).

## Authors and acknowledgment

- **Moritz Maehr** - _Initial work_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/academic-revealjs-template/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
