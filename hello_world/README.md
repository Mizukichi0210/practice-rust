# HELLO WORLD

## 実行手順

コンテナへ`exec`していることを前提

```bash
$ cd /practice-rust/hello_world

# Build
$ cargo build

# Run
$ ./target/debug/hello_world

# Build & run
$ cargo run
```

## 疑問点
~~コンパイル後に生成される `main` バイナリはgit管理すべきかどうか~~

~~よくわからないので、公式サイトを読み込みつつ考える。~~

`cargo build` で実行ファイルを生成する
