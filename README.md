# Business Card Jekyll Theme

To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!

## Installation

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: business-card-jekyll
```

or, in case you are using GitHub Pages, the line should be:

```yaml
remote_theme: J3-Tech/business-card-jekyll
```

## Usage

Add some or all of the following settings in the `_config.yml` file in order to configure your business card.
The majority of the settings are optional, while a few have predefined default values
(which can be overridden by assigning an empty string `""` as the value of that setting).

```yaml
# General settings
title: Business Card theme
author: John Doe

background:
  color: rgb(43,42,51)

foreground:
  color: whitesmoke

# Card info
card:
  titles: Software Engineer | Student

# Profiles
profiles:
  github: octocat
  youtube: user/YouTube
  twitter: twitter
  instagram: instagram
  facebook: facebook
  linkedin: company/linkedin
  stackoverflow: 1
  twitch: twitch
```

> Note: You can take a look at the `demo` branch of this repo for an example of how to setup the theme.

> Note: You can take a look at `https://business-card-jekyll.j3-tech.com/` to see 
> how the site should look like after being built.

## Development

To set up your environment to develop this theme, run `bundle install`.

The theme is setup just like a normal Jekyll site! To test the theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
