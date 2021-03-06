# AadhaarCheck

AadhaarCheck is a gem to validate a given aadhaar number. Aadhar number is generated using Verheoff Algorithm. The first 11 digits are the original numbers while the last one is a checksum.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'aadhaar_check'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install aadhaar_check

## Usage

Example Usage:

AadhaarCheck.valid? 1234 #-> false

AadhaarCheck.valid? 123412341234 #-> true

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/anuragverma65/aadhaar_check.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

