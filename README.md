# chss19

This is the website code for Clare Hall Summer Soiree 2019. It is built using Jekyll. The Jekyll theme/template used is Spectral by HTML5 UP ([link](https://github.com/arkadianriver/spectral)).

Please refer to the file `LICENSE.txt` carefully about terms of use.

## Running Jekyll
To run Jekyll, you need to install a Ruby on Rails environment. Instructions [here](https://gorails.com/setup/osx/10.13-high-sierra).

The `Gemfile` and `Gemfile.lock` files locks the Ruby gems at the correct version originally used to build the website. They match the version on GitHub (for easy hosting with GitHub pages). To build/serve website, run:
```
bundle exec jekyll serve
```

## Settings in _config.yml
These works best for hosting on an external server. I remember that for GitHub pages, `baseurl` might need to be set to `/` (to be checked).
```
baseurl:""
url:""
```

Set `destination` to where you want the website to be built. It should be the `public_html` folder on your external server.

