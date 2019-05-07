# LibreOffice Asia Conference 2019 site page

It uses [middleman](https://middlemanapp.com/)

## How to test it on your own computer

- install ruby 2.4.3
  - using [rbenv](https://github.com/rbenv/rbenv) or any alternatives is strongly recommended
- install `bundler` gem

```console
gem install bundler --no-doc
```

- use bundler to install whole middleman-related gems

```console
bundle install
```

- now you can generate the site like this:

```console
middleman server
```

- and you can see your own instance via http://localhost:4567
- enjoy!
