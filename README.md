# Blog Sparkland
--------------

### Commands:

bundle exec jekyll serve
bundle exec jekyll build

#### Global commands

jekyll build
jekyll serve 

## Installation on ubuntu:

### Ruby:
sudo apt install ruby-full ruby-rubygems build-essential zlib1g-dev
ruby -v
gem -v

### Jekyll

gem install bundler
gem install jekyll
bundle install


### RubyGems:
wget https://rubygems.org/rubygems/rubygems-3.5.17.tgzl
tar xvzf rubygems-3.5.17.tgz
cd rubygems-3.5.17
ruby setup.rb
gem -v

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler

### Install plugins exemples:
gem install jekyll-remote-theme 