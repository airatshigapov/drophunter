# Drophunter

Drophunter is a tool which downloads every public image it can find on [Droplr](https://droplr.com/).

This is very early version of gem. At this moment it downloads all images in your current folder.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'drophunter'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install drophunter

## Usage

Type of the following commands in your console:

`drophunter` will try all possible IDs (i.e. aaaa, aaab, aaac and so on)
`drophunter random` will try IDs in random order

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/drophunter. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

