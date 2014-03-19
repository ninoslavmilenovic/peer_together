# PeerTogether #

[![Build Status](https://travis-ci.org/pythogorian/peer_together.png?branch=master)](https://travis-ci.org/pythogorian/peer_together)

P2P RTC Service

## Development ##
```bash
~$ git clone git@github.com:pythogorian/peer_together.git
```

```bash
~$ cd peer_together
```

```bash
# make sure you are using ruby 2.1.1
peer_together$ export PT_SECRET_KEY_BASE="<at least 30 characters and all random>"
peer_together$ bundle install --path vendor/bundle
peer_together$ cp config/database.yml.example config/database.yml
# configure database connection in config/database.yml
peer_together$ bundle exec rake db:migrate
peer_together$ bundle exec rake db:seed
peer_together$ bundle exec rake db:test:prepare
peer_together$ bundle exec rspec
# all tests should pass
peer_together$ foreman start
# point your web browser to http://localhost:3000/
```

### Copyright ###
Copyright (c) 2014 Ninoslav Milenović

See LICENSE.txt for details.
