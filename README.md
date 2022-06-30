# EzColorize
Library to easily change the color of output text

## Example
```rust
use ez_colorize::ColorizeDebug;

#[derive(Debug)]
struct MyData{}

fn main() {
    let a = 23;
    println!("{}", a.red());

    let my_data = MyData{};
    println!("{}", my_data.blue());
}
```