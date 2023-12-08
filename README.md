# Sprite packer

This program compiles JSON spritesheets and the image counterpart to create
a `.spr` file, following the Argochamber's SPR specification.

## Usage

Download the SPR packer for Windows or Linux, then run the executable binary,
or alternatively you can download the repository and build it.

- [Windows binaries spr-pack.exe](https://github.com/sigmasoldi3r/spr-pack/releases/download/v1.0.0/spr-pack.exe)
- [Linux binaries spr-pack](https://github.com/sigmasoldi3r/spr-pack/releases/download/v1.0.0/spr-pack)

### Building

You will need the [Saturnus toolkit](saturnus) (Saturnus compiler + Janus).

Then just run:

```sh
janus build
```

And you will have the binaries at `dist/target/spr-pack`.

## Development

You can download the repository and make changes, just remember that you
will need the [Saturnus toolkit](saturnus).

[saturnus]: https://github.com/sigmasoldi3r/Saturnus
