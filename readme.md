Blog Sparkland
--------------

Commands:
jekyll build
jekyll serve

Installation on ubuntu:

Ruby:
sudo apt-get install ruby-full build-essential zlib1g-dev
ruby -v

RubyGems:
wget https://rubygems.org/rubygems/rubygems-3.5.17.tgz
tar xvzf rubygems-3.5.17.tgz
cd rubygems-3.5.17
ruby setup.rb
gem -v

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler

