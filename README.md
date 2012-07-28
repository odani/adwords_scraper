# AdwordsScraper

This gem scrapes the Adwords ads from a Google search engine results page, maps
it by position and then parses the title, description, display url, redirect,
sitelinks (if any), boxed warning (for pharma ads and if applicable) as well as
reviews text (if any).

## Installation

Add this line to your application's Gemfile:

    gem 'adwords_scraper'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install adwords_scraper

## Usage

Once installed, simply run the following (replace "green ipod" with your own
keyword text:

    AdwordsScraper.start("green ipod")

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
