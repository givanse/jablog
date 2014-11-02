
The site is powered by [Octopress](http://octopress.org/).

Site URL: http://jamesaltucher.aether.mx

## Contribute

If you would like to contribute a translation, just 
[add a file](https://github.com/aethermx/jamesaltucher/new/master/source/_posts) 
to the [_posts](https://github.com/aethermx/jamesaltucher/tree/master/source/_posts) folder.
You can copy the format from any of the files that are already there.

If you are not comfortable dealing with the technical aspects of Github, send me a message and I'll guide you.

## Run locally

    git clone git@github.com:aethermx/jamesaltucher.git
    cd jamesaltucher
    git pull octopress master
    # do not commit
    git reset HEAD
    git checkout

You need to install Ruby, then:

    gem install bundler
    bundle install

    # theme
    git clone git://github.com/lucaslew/whitespace.git .themes/whitespace
    rake install['whitespace']
    git checkout . 

    rake generate
    rake preview
