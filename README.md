# Anchor Collector 🦀

A tiny tool that collects stats from [Anchor](https://anchor.fm/).

It's written in Rust, and it was great fun to build.

I use it myself to check stats for my [podcast Ogrodje](https://anchor.fm/ogrodje).

## Usage

```bash
Usage: anchor-collector [OPTIONS] --email <EMAIL> --password <PASSWORD>

Options:
  -e, --email <EMAIL>
  -p, --password <PASSWORD>
  -f, --format <FORMAT>      [default: string] [possible values: string, json, csv]
  -h, --help                 Print help information
  -V, --version              Print version information
```

## Development

Get the latest Rust and then use cargo to build and run this thing.

```bash
$ cargo build --release
$ ./target/release/anchor-collector --help
```

## Author

- [Oto Brglez](https://github.com/otobrglez)

![Twitter Follow](https://img.shields.io/twitter/follow/otobrglez?style=social)
