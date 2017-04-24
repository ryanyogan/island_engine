# Island Engine

A simple engine that will spawn new Agent processes under a supervised tree
for each game of "Island" a.k.a Battleship but without the lawsuit.

This application will be serving websockets via Channels through Phoenix as a mixed in module.  Documentation to come.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `island_engine` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:island_engine, "~> 0.1.0"}]
    end
    ```

  2. Ensure `island_engine` is started before your application:

    ```elixir
    def application do
      [applications: [:island_engine]]
    end
    ```
