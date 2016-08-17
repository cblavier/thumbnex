# Thumbnex

[![Build Status](https://travis-ci.org/talklittle/thumbnex.svg?branch=master)](https://travis-ci.org/talklittle/thumbnex)

Elixir library to generate thumbnails from images and videos.

Documentation: https://hexdocs.pm/thumbnex/

## Example

```elixir
Thumbnex.create_thumbnail("/path/to/input.mp4", "/path/to/output.jpg", max_width: 200, max_height: 200)
```

## Prerequisites

* [ImageMagick](https://imagemagick.org)
* [FFmpeg](https://ffmpeg.org)

## Installation

  1. Add `thumbnex` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:thumbnex, "~> 0.1.0"}]
    end
    ```

  2. Ensure `thumbnex` is started before your application:

    ```elixir
    def application do
      [applications: [:thumbnex]]
    end
    ```

## Release notes

See the [changelog](CHANGELOG.md) for changes between versions.

## License

Thumbnex source code is licensed under the [MIT License](LICENSE.md).