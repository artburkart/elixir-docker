## A Docker container for Elixir programming language

Elixir is a generally awesome functional programming language that runs on the Erlang VM.

## Create an Elixir app

```console
$ docker run -it --rm -v "$PWD":/name_of_app artburkart/elixir:latest mix new name_of_app
```
