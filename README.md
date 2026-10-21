### Learn rust docs
documenting my journey learning rust :smiley: :crab:
</br>
</br>
</br>
## 15/10/2026
```
rustup
rustc
```
```rustup``` is the toolchain manager. ```rustc``` is the official compiler, ```rustc [project_name]``` and then ```./[project_name]``` to compile and execute. :crab:
</br>
</br>
</br>
## 20/10/2026
The *Cargo.toml(*Tom’s Obvious, Minimal Language*)* has 2 sections:
- ```[package]```  indicates that the following statements are configuring a package
- ```[dependencies]``` list any of the project’s dependencies
</br>

```
cargo build
cargo run
cargo build --release
```
```cargo build```, which puts the executable ```[project_name].exe``` file in the *target/debug* directory, goes with ```./target/debug/[project_name]``` to build and execute the program. ```cargo run``` does both. ```cargo build --release```, which puts the executable in *target/release* instead of *target/debug*, compiles the project with **optimizations**. Intending for real use instead of program testing/frequent rebuilding.
</br>
It is easier to work with ```cargo``` as the project become more intricate. :package:
