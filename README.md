# Couscous

Couscous is great. Couscous generates a website from your markdown documentation.


## Introduction

[Github pages](http://pages.github.com/) are good, but what do you do:

* if you want to write your documentation in **Markdown** and not in HTML?
* if you want your documentation to be transformed into a **website**?
* if you want to **keep the documentation with your code**, versioned in the repository?

*Couscous* is here to help you. **Your documentation is written in Markdown,
versioned in your repository with your source, compiled to HTML and published to *Github pages*.**


## How does it work

1. you write your README and documentation in `.md` files (Markdown) on your repository
2. you generate you website with *Couscous*
  - it turns `.md` files into HTML files
  - HTML files are committed to the `gh-pages` branch of your repository, and thus are published as a website by Github
3. profit!


## Features

* preview your website using `couscous preview`
* write your website template using Twig
* Markdown compiler supports GitHub fenced code blocks
* easily extensible, clean PHP code


## Installation

```
wget http://mnapoli.fr/Couscous/couscous.phar
chmod +x couscous.phar
sudo mv couscous.phar /usr/local/bin/couscous
```


## Usage

```
$ couscous generate
$ couscous preview
$ couscous deploy
```


## Generating the phar

To generate the phar archive yourself, check out the repository and:

```
$ composer install
$ bin/compile
```

The phar is generated as `bin/couscous.phar`.


## Read more

* [Documentation](docs/)


## Contribute

Follow the project [on Github](https://github.com/mnapoli/Couscous/)