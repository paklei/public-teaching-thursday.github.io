# public-teaching-thursday.github.io
docs related to the meetings

Installation notes

- ruby
brew install ruby
export PATH=/usr/local/opt/ruby/bin:$PATH

-jekyll
sudo gem install bundler
sudo gem install -n /usr/local/bin/ jekyll

ruby -v
ruby 2.6.3p62 (2019-04-16 revision 67580)

then replace the first two digits from ruby version (2.6) into the following line
export PATH=$HOME/.gem/ruby/X.X.0/bin:$PATH will be export PATH=$HOME/.gem/ruby/2.6.0/bin:$PATH

Note: if you are a windows user, please uncomment the last gems on the bottom of the Gemfile in order to be able to compile the project

- gem github-pages
sudo gem install github-pages

- gem jekyll
sudo gem install jekyll -v 3.8.5

- run locally
bundle exec jekyll serve

you could also check the following links:
https://jekyllrb.com/docs/installation/macos/
https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll
https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll
https://pages.github.com/versions/
