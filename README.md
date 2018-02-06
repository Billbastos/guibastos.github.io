
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

## Jekyll ##

```bash
gem install jekyll bundler
```


# Creating a new Jekyll project #

```bash
jekyll new [site-name]
```