# ElephantlyCouscous
A theme for couscous by Elephantly

[Read The Docs](https://readthedocs.org/) builds websites using a Sphinx theme. [That theme](https://github.com/snide/sphinx_rtd_theme) is open source and released under the MIT license.

## Usage

To use the template, set it up in your `couscous.yml` configuration file:

```yaml
template:
    url: https://github.com/elephantly/ElephantlyCouscous
```

## Configuration

Here are all the variables you can set in your `couscous.yml`:

```yaml
# Base URL of the published website
baseUrl: http://username.github.io/project

# Used to link to the GitHub project
github:
    user: myself
    repo: my-project

title: My project
subTitle: This is a great project.

# The left menu bar
menu:
    items:
        home:
            text: FAQ
            # You can use relative urls
            relativeUrl: doc/faq.html
        foo:
            text: Another link
            # Or absolute urls
            absoluteUrl: https://example.com
```

This template configuration is base on the excellent [Template-ReadTheDocs](https://github.com/CouscousPHP/Template-ReadTheDocs)
