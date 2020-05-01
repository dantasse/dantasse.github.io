dantasse.github.io
==================

Well, here is my website. Some props:

- Modernizr
- Jekyll http://jekyllrb.com/
- config.yml from Asymmetrical View http://asymmetrical-view.com/2009/05/14/starting-wtih-jekyll.html
- Bootstrap http://twitter.github.com/bootstrap/
- http://24ways.org/2012/how-to-make-your-site-look-half-decent/
- http://designshack.net/articles/css/10-great-google-font-combinations-you-can-copy/

## Memo to my future self

To keep this thing going:
[github pages docs](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#keeping-your-site-up-to-date-with-the-github-pages-gem)

Last time I did this (2020-05-01) the magic words were:

Ensure you have rvm:

```
\curl -sSL https://get.rvm.io | bash -s stable
```

Ensure that you have the correct version of Ruby installed:

```
rvm install (some version)
```
(I don't know how to figure out the most recent version - maybe [check here](https://www.ruby-lang.org/en/downloads/))

Ensure you have bundler installed and update things in bundler

```
gem install bundler

bundle update
bundle exec jekyll serve
```
and mid bundle update because something failed, I had to: 
```
cd /usr/local/opt/readline/lib    
ln libreadline.8.dylib libreadline.7.dylib
```
