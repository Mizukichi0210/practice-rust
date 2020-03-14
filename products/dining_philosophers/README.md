## 食事する哲学者

最終的な想定結果と実際の実行結果が異なる。

気になるので、なぜそうなっているかを調べまとめる。

```bash
# 想定結果
$ cargo run
   Compiling dining_philosophers v0.1.0 (/practice-rust/products/dining_philosophers)
    Finished dev [unoptimized + debuginfo] target(s) in 2.95s
     Running `target/debug/dining_philosophers`
Gilles Deleuze is eating.
Emma Goldman is eating.
Emma Goldman is done eating.
Gilles Deleuze is done eating.
Judith Butler is eating.
Karl Marx is eating.
Judith Butler is done eating.
Michel Foucault is eating.
Karl Marx is done eating.
Michel Foucault is done eating.

# 実際の実行結果(Docker container内)
$ cargo run
   Compiling dining_philosophers v0.1.0 (/practice-rust/products/dining_philosophers)
    Finished dev [unoptimized + debuginfo] target(s) in 2.95s
     Running `target/debug/dining_philosophers`
Emma Goldman is eating.
Emma Goldman is done eating.
Karl Marx is eating.
Karl Marx is done eating.
Gilles Deleuze is eating.
Gilles Deleuze is done eating.
Judith Butler is eating.
Judith Butler is done eating.
Michel Foucault is eating.
Michel Foucault is done eating.
```