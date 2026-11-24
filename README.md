# The Twelve Days of Christmas

A small Rust program that prints the lyrics to the Christmas carol "The Twelve Days of Christmas". Instead of typing out every verse, the program uses loops to take advantage of the song's repetition.

## How it works

The program stores the twelve day names (first, second, third, and so on) in one array and the twelve gifts in another. An outer `for` loop goes through each day and prints the opening line, and an inner loop counts backwards from that day's gift down to the partridge, so every verse lists its gifts in the correct order. From the second day onward, the last line becomes "And a partridge in a pear tree", just like in the song.

## What it demonstrates

This project practices arrays, `for` loops with ranges (`0..12` and `(0..=day).rev()`), nested loops, indexing into arrays, `if`/`else` expressions, and printing with `println!`.

## Requirements and how to run

You need Rust and Cargo installed (get them from https://rustup.rs). Clone the repository, move into the project folder, and run `cargo run` to print all twelve verses.

## Example output

The first verse prints "On the first day of Christmas, my true love gave to me:" followed by "A partridge in a pear tree", while the second verse prints "On the second day of Christmas, my true love gave to me:" followed by "Two turtle doves" and then "And a partridge in a pear tree".