# Note to BrightHivers

This is a [Jekyll](https://jekyllrb.com/) theme forked from [just-the-docs](https://github.com/pmarsceill/just-the-docs). As of 08/17/2020, it is barely altered from the original. This repo, **under this name** (bh-just-the-docs-theme) is the source of the **remote theme** underlying the resource library hosted in the repo called `316ef7d8c202d47efb6d457ebe842927d2cb746d`. If the name of this directory is changed, the resource library will **break**.

## Why are we hosting this forked theme ourselves?

There are two ways to serve Jekyll blogs on GitHub Pages. The first is to build the blog locally and then commit it to the associated repo. This requires some familiarity with the command line. The second way is to simply upload the markdown files that make up the blog and point Jekyll to a **remote theme**. In this second case, it is not necessary to build the site locally: additions can be made simply by uploading markdown files.

To save (comparatively) nontechnical BH employees the trouble of building the blog locally, I've chosen the second path here. Additionally, the original `just-the-docs` repo is still under development, so changes made by its developer will appear on the pages we are using it as a template for. This problem is solved by forking the original repo and pointing the resource library here as the remote theme.

This will also allow us to continue making design changes to the layout in perpetuity.


<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/pmarsceill/just-the-docs/actions?query=workflow%3A%22Master+branch+CI%22"><img src="https://github.com/pmarsceill/just-the-docs/workflows/Master%20branch%20CI/badge.svg" alt="Build status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">Just the Docs</h1>
    <p align="center">A modern, highly customizable, and responsive Jekyll theme for documentation with built-in search.<br>Easily hosted on GitHub Pages with few dependencies.</p>
    <p align="center"><strong><a href="https://pmarsceill.github.io/just-the-docs/">See it in action!</a></strong></p>
    <br><br><br>
</p>

![jtd](https://user-images.githubusercontent.com/896475/47384541-89053c80-d6d5-11e8-98dc-dba16e192de9.gif)

## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "just-the-docs"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: just-the-docs
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install just-the-docs

## Usage

[View the documentation](https://pmarsceill.github.io/just-the-docs/) for usage information.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pmarsceill/just-the-docs. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

### Submitting code changes:

- Open a [Pull Request](https://github.com/pmarsceill/just-the-docs/pulls)
- Ensure all CI tests pass
- Await code review
- Bump the version number in `just-the-docs.gemspec` and `package.json` according to [semantic versioning](https://semver.org/).

### Design and development principles of this theme:

1. As few dependencies as possible
2. No build script needed
3. First class mobile experience
4. Make the content shine

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
