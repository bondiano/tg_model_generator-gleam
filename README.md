# tg_model_generator

This project generates the `model.gleam` file from the Telegram Bot API documentation.

Almost all of model types can be auto-generated from the API documentation, but some cases are not supported by the auto-generated code (e.g. generic type encoders, some API params, etc).

## Requirements

- Elixir
- Gleam

## Development

```sh
make run   # Run the project
```
