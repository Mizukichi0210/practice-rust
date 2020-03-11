# practice-rust

[doc.rust-jp.rs/](https://doc.rust-jp.rs/the-rust-programming-language-ja/1.6/book/guessing-game.html)のサンプルコードを実際に動かしてみたリポジトリ

## 実行手順

```bash
# Build
$ docker build . -t practice-rust

# Create container and exec container
$ docker run --rm -v $(pwd):/practice-rust -it practice-rust:latest /bin/bash
```
