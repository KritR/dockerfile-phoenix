# Dockerfile Phoenix

This Dockerfile is for Elixir Phoenix and comes pre installed with Rebar, Hex, and Buildtools

## Usage

To start up your phoenix server 
```docker run -it --rm -v "$PWD":/code kritr/phoenix mix phx.server```

To run a migration
```docker run -it --rm -v "$PWD":/code kritr/phoenix mix setup```

and so on
