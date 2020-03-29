# Local Setup

## Prerequisites

* PostgreSQL
* Ruby 2.7.0

## Installation

1. Clone this repo
    ```
    git clone https://github.com/matlagp/habbit.git
    cd habbit
    ```
2. Make sure you're using Ruby 2.7:
    ```
    ruby --version
    ```
3. Install [bundler](https://github.com/rubygems/bundler)
    ```
    gem install bundler
    ```
4. Install gem dependencies
    ```
    bundle install
    ```
    
## Configuration

Create local database
```
cp config/database.example.yml config/database.yml
bundle exec rails db:create
```

## Verification

Running local server
```
bundle exec rails server
```
