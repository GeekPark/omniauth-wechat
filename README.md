# Omniauth::Wechat


## Installation

Add this line to your application's Gemfile:

    gem 'omniauth-wechat', git: 'https://github.com/GeekPark/omniauth-wechat.git'

And then execute:

    $ bundle

## Usage
```ruby
Rails.application.config.middleware.use OmniAuth::Builder do
  provider :wechat, YOUR_WECHAT_APP_ID, YOUR_WECHAT_SECRET
end
```