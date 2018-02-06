
# Installation #


## Ruby ##

  `\curl -sSL https://get.rvm.io | bash -s stable`
  `rvm list known`
  `rvm install "ruby-2.4.2"`
  `ruby -v`
  `rvm use ruby-2.4.2 --default`

  ### Optional: ###

    > In case of installation error run this command befrore install again
    > `xcode-select --install`

    > *OR*
    > `softwareupdate --list`
    > `softwareupdate --install <product name>`

    > *OR*
    > `$ rm -rf /Library/Developer/CommandLineTools`
    > `xcode-select --install`

    > *OR*
    > `rvm install "ruby-2.2.5"`
    > `rvm use ruby-2.2.5 --default /* sudo rvm osx-ssl-certs update all */`


## Jekyll ##

  `gem install jekyll bundler`

