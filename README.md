# Mandelbrot

This program generates the Mandelbrot set using the Escape Time algorithm and renders a PNG image of it.

#### To run:

* Install [rust](https://rustup.rs/)
* Clone the repo
* In your terminal, create an optimized build: `cargo build --release`
* It will install its dependencies and build an executable
* Run it! `./target/release/mandelbrot mandel_01.png 4000x3000 -2.3,-1.48 0.66,1.48`

Here is an example image from running the above:

![alt text](https://github.com/DamianRivas/mandelbrot/blob/master/mandel.png "Example image of a Mandelbrot set")

Enjoy :)
