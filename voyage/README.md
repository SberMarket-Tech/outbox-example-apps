# Voyage

This is an example application which uses:
- [sbmt-outbox](https://github.com/SberMarket-Tech/sbmt-outbox)
- [sbmt-kafka_consumer](https://github.com/SberMarket-Tech/sbmt-kafka_consumer)

It allows you to learn how to use the Outbox pattern and how it works with Ruby on Rails.

## Development

1. Install deps and prepare DB

```shell
dip infra up
dip provision
```

2. Run Puma server

```shell
dip rails s
```

3. Run tests

```shell
dip rake db:create db:migrate RAILS_ENV=test
dip rspec
```
