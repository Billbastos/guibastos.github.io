
# Installation #

## Ruby ##

```bash
\curl -sSL https://get.rvm.io | bash -s stable
rvm list known
rvm install "ruby-2.4.2"
ruby -v
rvm use ruby-2.4.2 --default
```

### Optional: ###

In case of installation error run this command befrore install again
```bash
xcode-select --install
```

**OR**
```bash
softwareupdate --list
softwareupdate --install <product name>
```

**OR**
```bash
$ rm -rf /Library/Developer/CommandLineTools
xcode-select --install
```

**OR**
```bash
rvm install "ruby-2.2.5"
rvm use ruby-2.2.5 --default 
# sudo rvm osx-ssl-certs update all
```

For more information access:
[Jekyll Installation Guide](https://jekyllrb.com/docs/installation/)

## Jekyll ##

```bash
gem install jekyll bundler
```

# Creating a new Jekyll project #

```bash
jekyll new [site-name]
```

## Serving the website ##
```bash
# First time 
cd/[site-name]
bundle exec jekyll serve

# If it's not the first time running the server
jekyll serve

# To have access to the _drafts folder
jekyll serve --draft
```

## Installing a new Theme

- [Select a theme on Rubygems](https://rubygems.org/) and search for jekyll-theme
- Copy the name of the theme
- Go over Gemfile and add the line below
- gem "[theme-name]"
- on the Terminal, run `bundle install`
- Head over the _config.yml file and change the `theme` variable adding the new theme name
- start jekyll running `bundle exec jekyll serve`
