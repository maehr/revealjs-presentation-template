# Reveal.js presentation template

[revealjs-presentation-template](https://maehr.github.io/revealjs-presentation-template/) is a simple template for presentations written in [Markdown](https://daringfireball.net/projects/markdown/) using [Reveal.js](https://github.com/hakimel/reveal.js/), [Jekyll](https://jekyllrb.com/) and [HTML5Boilerplate](https://html5boilerplate.com/). It can be hosted on [GitHub Pages](https://pages.github.com/).

[![GitHub issues](https://img.shields.io/github/issues/maehr/revealjs-presentation-template.svg)](https://github.com/maehr/revealjs-presentation-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/revealjs-presentation-template.svg)](https://github.com/maehr/revealjs-presentation-template/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/revealjs-presentation-template.svg)](https://github.com/maehr/revealjs-presentation-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/maehr/revealjs-presentation-template.svg)](https://github.com/maehr/revealjs-presentation-template/blob/master/LICENSE.md)

## Usage

- Click on [Use the template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) or [fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) this repo.
- Activate [GitHub Pages](https://pages.github.com/) in repository settings and set [source](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source) to `master branch /docs folder`.
- Change `docs/index.md` and push your commit.
- Enjoy your presentation <https://maehr.github.io/revealjs-presentation-template/>

## Installation

- Click on [Use the template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) or [fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) this repo.
- [Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) it.
- Install [Ruby](https://jekyllrb.com/docs/installation/), and install [Jekyll with Bundler](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/) to run [revealjs-presentation-template](https://maehr.github.io/revealjs-presentation-template/) locally. Make sure you are in the `docs`directory.

```bash
git submodule init
git submodule update --remote
cd ./docs
gem install jekyll bundler
bundle exec jekyll serve
```

## Support

This project is maintained by [@maehr](https://github.com/maehr). Please understand that we won't be able to provide individual support via email. We also believe that help is much more valuable if it's shared publicly, so that more people can benefit from it.

| Type                   | Platforms                                                    |
| ---------------------- | ------------------------------------------------------------ |
| 🚨 **Bug Reports**      | [GitHub Issue Tracker](https://github.com/maehr/revealjs-presentation-template/issues) |
| 🎁 **Feature Requests** | [GitHub Issue Tracker](https://github.com/maehr/revealjs-presentation-template/issues) |

## Roadmap

- Support for [custom themes](https://github.com/hakimel/reveal.js/blob/master/css/theme/README.md)
- Removal of HTML tags (`<section>` etc.) inside Markdown slides via a smart Jekyll template
- Replace MathJax CDN link with `docs/assets/vendor/MathJax`
- More options via YAML front matter.
- Make MathJax optional

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/maehr/revealjs-presentation-template/tags).

## Authors and acknowledgment

- **Moritz Maehr** - _Initial work_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/revealjs-presentation-template/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
