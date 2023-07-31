# Dungeon Crawler in Rust

This repository contains the source code for a dungeon crawler game created using the Rust programming language. The project demonstrates the use of popular crates in the Rust ecosystem, Legion and bracket-lib, to create an exciting dungeon crawl experience.

## About the Game

The objective of the game is to navigate through a dynamic and engaging dungeon environment, with the ultimate goal of finding a special item known as "YALA" (Yet Another Lost Amulet). Be aware, though! The dungeon is filled with dangers and obstacles that players must overcome.

The game incorporates procedural map generation, using the Cellular Automata and Drunkard's Walk algorithms to create randomized dungeon and forest environments. This ensures that no two gaming experiences are alike!

![Game Screenshot](https://github.com/luis-prates/dungeoncrawl/assets/80156766/27e8e453-fcdc-403d-8137-38d8bf299f74)

## Game Mechanics

* **Movement**: You can navigate through the game world using the arrow keys.
* **Health Recovery**: You can recover health by pressing the space bar.
* **Enemies**: Stay alert! Enemies roam the dungeon and could pose a threat to your journey.
* **End Goal**: Your objective is to find the YALA. Will you survive long enough to locate it?

## Tech Stack

The game was developed using the Rust programming language and relies on the following major components:

* **Legion**: An efficient and feature-rich ECS (Entity Component System) that enables a flexible game architecture.
* **Bracket-lib**: A toolkit for developing roguelike games, providing capabilities such as console rendering, navigation, and noise generation.

## Setup

Ensure you have [Rust](https://www.rust-lang.org/tools/install) installed in your local environment.

1. Clone this repository:
```
git clone https://github.com/luis-prates/dungeoncrawl.git
```

2. Navigate into the cloned directory and build the game:
```
cd dungeoncrawl
cargo build --release
```

3. Run the game:
```
cargo run --release
```

## Acknowledgements

This project was created by following the tutorial book "Hands-on Rust: Effective Learning through 2D Game Development and Play" by Herbert Wolverson. If you're interested in learning Rust and game development, I highly recommend this book!

Enjoy playing!
