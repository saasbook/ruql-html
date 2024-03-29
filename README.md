# Ruql::Html

This formatter requires [ruql](https://github.com/saasbook/ruql) and
allows formatting RuQL quizzes as HTML.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ruql-html'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ruql-html

## Usage

The simplest usage is `ruql html quizfile.rb > output.html`.
`ruql html -h` shows options that let you specify a different HTML/CSS
template, among other things.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/saasbook/ruql-html. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Code of Conduct

Everyone interacting in the Ruql::Html project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/saasbook/ruql-html/blob/master/CODE_OF_CONDUCT.md).
