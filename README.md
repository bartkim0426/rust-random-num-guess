## Rust first example



- [`The Rust Programming Language`](https://doc.rust-lang.org/book/2018-edition/ch02-00-guessing-game-tutorial.html)의 `Guessing Game` 예시


- `let guess: u32 = ...`와 같이 `u32`, `u64` 등의 타입으로 변환
- `read_line()`, `trim().parse()`와 같이 exception handling이 필요한 경우 `expect`를 필수로 써주어야 컴파일 에러가 나지 않음
- `match`를 사용해서 `Ok`, `Err` 결과를 반환 (`Result` 타입)하는 방식으로 사용 가능
- `cargo doc --open` 명령어로 사용된 library의 문서를 확인 가능
