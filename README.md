# Grape::Middleware::Logstasher
Logstash comptible access logs for Grape 0.12.0

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'grape-middleware-logstasher'
```

## Usage
```ruby
class API < Grape::API
  use Grape::Middleware::Logstasher
end
```

## Contributing

1. Fork it ( https://github.com/ridiculous/grape-middleware-logstasher/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
