# Pineapple

Pineapple is a minimalistic [Jekyll](https://jekyllrb.com) portfolio theme that focuses on putting your projects in the spotlight.

![Pineapple screenshot](https://user-images.githubusercontent.com/9528895/38713105-6dda8a74-3ec7-11e8-8062-8aa6cf24c795.jpg)

See Pineapple in action on the [demo site](https://arnolds.io/pineapple/).

## Contents

- [Setup](#setup)
- [Deploy to Github Pages](#deploy-to-github-pages)
- [Creating projects](#creating-projects)
- [Resources](#resources)
- [License](#license)

## Setup

Install dependencies:

```
$ gem install jekyll bundler
```

Pulldown the project:

```
$ git clone git@github.com:arnolds/pineapple.git
$ cd pineapple
```

Start Jekyll:

```
$ jekyll serve
```

Browse to http://127.0.0.1:4000/pineapple/ for some Pineapple goodness.

## Deploy to Github Pages

1. Fork this repository, then rename the repository to yourgithubusername.github.io.
2. Update user configuration values in `_config.yml`, and also set `baseurl: ""`.

## Creating projects

Projects are created as `.md` documents within the `_posts/projects` directory. They follow the same naming conventions as regular [Jekyll posts](https://jekyllrb.com/docs/posts/). Pineapple comes with four example projects, which you should use as a guide for creating your own e.g. [Red Pineapple](_posts/projects/2017-04-01-redpineapple.md).

## Resources

- [Apple Devices PSD Mockup Templates](https://www.graphicsfuel.com/2016/04/apple-devices-psd-mockup-templates/)

## License

Open sourced under the [MIT license](LICENSE.md).
