# ruqqus-rust

## Intro

Ruqqus-rust is a reimplementation of the original python Ruqqus server, this project is totally written in Rust and RESTful.

## Compile

To compile it directly, run `cargo build`, to run `cargo run`.

## Dockerfile

Please mind that compiling the project using Dockerfile is slow since it's in release mode.

TO build the server:

```
docker build -t ruqqus .
``` 

To start the server: 

```
docker run -v -it --rm -p 7700:7700 ruqqus
```

## License
[MPL-2.0](https://github.com/ruqqus/ruqqus/blob/master/LICENSE)
