# Guard::Foodcritic

[![Gem Version](https://badge.fury.io/rb/guard-foodcritic.png)](http://badge.fury.io/rb/guard-foodcritic)

[![Build Status](https://travis-ci.org/Nordstrom/guard-foodcritic.png?branch=master)](https://travis-ci.org/Nordstrom/guard-foodcritic)

[![Inline docs](http://inch-ci.org/github/nordstrom/guard-foodcritic.svg?branch=master)](http://inch-ci.org/github/nordstrom/guard-foodcritic)

[![Code Climate](https://codeclimate.com/github/Nordstrom/guard-foodcritic/badges/gpa.svg)](https://codeclimate.com/github/Nordstrom/guard-foodcritic)

Guard::Foodcritic automatically runs foodcritic.

## Installation

Please be sure to have [Guard](https://github.com/guard/guard) installed before continuing.

Install the gem:

    $ gem install guard-foodcritic

Add the guard-foodcritic definition to your Guardfile by running this command:

    $ guard init foodcritic

## Options

```ruby
:all_on_start => false    # Whether to run Foodcritic on all cookbooks at startup
                          # default: true

:cli => "--epic-fail any" # Command line arguments passed to foodcritic
                          # default: "--epic-fail any"

:cookbook_paths => "."    # The path(s) to your cookbooks
                          # default: ["cookbooks"]

:notification => false    # Whether to display notifications after the lint is done running
                          # default: true
```
