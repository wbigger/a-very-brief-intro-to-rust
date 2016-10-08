# a-very-brief-intro-to-rust

## install rust

The best way to install Rust is with [rustup]. [rustup] is a Rust
version manager. To install it type:

```
curl https://sh.rustup.rs -sSf | sh
```

To keep your rust up-to-date with the latest stable version of rust,
type:

```
rustup update
```

To check which version of Rust you have type:

```
rustc -- version
```

## setting up a project

There are many ways to setup a project in Rust, but this is the simplest.

1. Create a repository on Github
2. Clone the repository
3. `cd` into the repository directory
4. Type `cargo init .`

This will create several files and folders for you automatically:

- `Cargo.toml`: metadata about your project and it's dependencies
- `.gitignore`: ignores compiled files built by Rust
- `src/lib.rs`: where your Rust code goes (change this to `main.rs` if you are not writing a library)

#### `lib.rs` vs `main.rs`

There are 2 main types of projects you can make in Rust. A library and not
a library. 

If you are writing a <strong>library</strong>, it means you intend for your
code to be used in someone else's application as a crate or module.
If you want to do this, you should use a `lib.rs`.

If you are writing a <strong>not library</strong>, it means that you'd like
to write code that compiles into a binary that someone can run. If you 
want to do this, you need to use a `main.rs`. Inside the `main.rs` you 
should have a `main` function that looks like this:

```rust
fn main() {
  /// your app code goes here
}
```

## function signatures

## dealing with strings

## `println!` and `format!`

## the `Option` and `Result` types

## `match` syntax
