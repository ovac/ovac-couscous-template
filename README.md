# OVAC Couscous Template


```md
 Follow me anywhere @ovac4u                         | GitHub
 _________                          _________       | Twitter
|   ___   |.-----.--.--.---.-.----.|  |  |.--.--.   | Facboook
|  |  _   ||  _  |  |  |  _  |  __||__    |  |  |   | Instagram
|  |______||_____|\___/|___._|____|   |__||_____|   | Github + @ovac
|_________|                        www.ovac4u.com   | Facebook + @ovacposts
```


## Introduction
A template for couscous generated static html documents by ![OVAC4U](`https://www.ovac4u.com`) inspired by the [ElephantlyCouscous](https://github.com/elephantly/ElephantlyCouscous) template design and the [Template-Dark](https://github.com/CouscousPHP/Template-Dark) template configuration with widgets and google analytics.

[Read The Docs](https://readthedocs.org/) builds websites using a Sphinx template. [That template](https://github.com/snide/sphinx_rtd_template) is open source and released under the MIT license.

Curious about seeing what it looks like? checkout the [OVAC\Hubtel-Payment](`https://ovac4u.com/packages/hubtel-payment`) composer package official documentation generated using this theme and configuration.

## Usage

To use the template, set it up in your `couscous.yml` configuration file in the root of your project:

```yaml
template:
    url: https://github.com/ovac/ovac-couscous-template
```

## Configuration

Here are all the variables you can set in your `couscous.yml`:

```yaml
# Your base URL to which the website will be published
# baseUrl: http://www.example.com

# Used to link to the GitHub project
github:
    # your github username
    user: your-github-username

    # your github repo
    repo: your-github-repo

widgets:
    # Your addthis key from your addthis application.
    addthis: ra-XXXXXXXXXXXX

    # Your google analytics key
    googleAnalytics: UA-XXXXXXX-X

    # Your google tag manager key
    googletag: GTM-XXXXXXX

template:
    # the github url for this template. !Dont change this if you want this theme.
    url: https://github.com/ovac/ovac-couscous-template

include:
    # Specify the folders where your markdown files live
    - .
    - docs

exclude:
    # specify folders to be ignored by the scanner
    - vendor

# A title of the documentation website
title: OVAC Couscous template

# A subtitle for the documentation website
subTitle: it's beautiful.

# The left menu bar
menu:
    sections:
        introduction:
            name: Introduction
            items:
                home:
                    text: Home
                    relativeUrl:
        getting-started:
            name: Getting Started
            items:
                installation:
                    text: Installation
                    relativeUrl: installation.html
        
        guide:
            name: Guide
            items:
                config:
                    text: Config
                    relativeUrl: config.html
        
        api:
            name: Api
            items:
                api:
                    text: Api
                    relativeUrl: api/index.html

                coverage:
                    text: Coverage
                    relativeUrl: coverage/index.html
        
        links:
            name: Links
            items:
                external-documentation:
                    text: External Official Documentation
                    absoluteUrl: https://some-website
                
                external-swagger:
                    text: Api Swagger UI
                    absoluteUrl: https://some-website
```

This template configuration is based on the excellent [Template-Dark](https://github.com/CouscousPHP/Template-Dark)


