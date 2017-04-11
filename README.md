# Rusty dark syntax theme for Atom

> Notice: If you have `atom-language-rust` package installed,
> it will override various colors defined in this theme.
>
> To make sure this theme looks as advertised, __uninstall__ `atom-language-rust`,
> __install__ `language-rust` (or `language-rust-redux`), and restart __Atom__.

The main motivation was to make a syntax theme that works well for the
[Rust](https://www.rust-lang.org/) language. All I needed was suitable
inspiration. How would rusty theme look like? Let's see:

![Rusty Inspiration](https://raw.githubusercontent.com/Nercury/atom-rusty-dark-syntax/master/examples/rust-inspiration.jpg)

Of course, I tried not overdo it and keep it functional. This resulted in
following choices:

- Actual code is a bit brown
- Keywords and types favor blue
- Control structures use a very distinct green
- Type bounds favor brown
- Comments are readable grey
- Strings are green
- There are colors to hint very special cases, like unsafe

Of course, I also tested it with other languages, in particular: `js`, `html`, `css`,
`less`, `java`, `lua`, `php`, `bash`, `toml`, `markdown`, `protobuf`, `sql`.

The result:

![Screenshot](https://raw.githubusercontent.com/Nercury/atom-rusty-dark-syntax/master/examples/screenshot.jpg)
