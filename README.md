# WebCuratorTool

## About the Web Curator Tool suite of applications

The Web Curator Tool is a suite of tools and applications for managing the selective web harvesting process. It is
typically used at national libraries and other collecting institutions to preserve online documentary heritage.

Unlike previous tools, it is enterprise-class software, and is designed for non-technical users like librarians.
The software was developed jointly by the National Library of New Zealand and the British Library, and has been
released as free software for the benefit of the international collecting community.

## Where to find more information

The primary source for WebCurator Tool documentation is the [WebCurator documentation repository](https://github.com/WebCuratorTool/webcurator-docs). This documentation
covers the various components that interact and work with each other to complete the selective web harvesting process.


## Contributors

See individual git commits for code authorship. Issues are tracked through the git repository issue tracker.


## License

&copy; 2006 - 2018 The National Library of New Zealand, Koninklijke Bibliotheek and others. See individual
commits to determine code authorship. Apache 2.0 License.

## Building and Running This Site Locally

To build this site locally you first need to install Jekyll.  The Ubuntu commands are:
-  sudo apt install ruby-full build-essential zlib1g-dev
-  sudo gem install jekyll bundler


From within your `WebCuratorTool.github.io` directory, use command 
- bundle install

For other operating system instructions go to https://jekyllrb.com/docs/installation/.  If you have problems installing the bundler
you may need to check your gems directory permissions.

To build without starting the server, go to your `WebCuratorTool.github.io` directory and use command
-  bundle exec jekyll build

To start the server locally, go to your `WebCuratorTool.github.io` directory and use command
-  bundle exec jekyll serve

By default this site will be available on http://127.0.0.1:4000/.

## Minimal Mistakes Jekyll theme

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll.svg)](https://rubygems.org/gems/minimal-mistakes-jekyll)


This site uses the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).  Minimal Mistakes is a flexible two-column Jekyll theme, perfect for 
building personal sites, blogs, and portfolios. As the name implies, styling is purposely minimalistic to be enhanced and customized by 
you :smile:.

**Note:** The theme uses the [jekyll-include-cache](https://github.com/benbalter/jekyll-include-cache) plugin which will need to be installed in your `Gemfile` and added to the `plugins` array of `_config.yml`. Otherwise you'll encounter `Unknown tag 'include_cached'` errors at build.

[![Minimal Mistakes live preview][2]][1]

[1]: https://mmistakes.github.io/minimal-mistakes/
[2]: screenshot.png (live preview)

![layout examples](screenshot-layouts.png)
