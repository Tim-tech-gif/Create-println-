# Create-println-
fn main() {     const WIDTH: usize = 10;  // ширина конверта     const HEIGHT: usize = 5;  // висота конверта      let mut envelope = String::new();      for i in 0..HEIGHT {         for j in 0..WIDTH {             if i == 0 || i == HEIGHT - 1 {                 envelope.push('*');  // верхня і нижня межі             
