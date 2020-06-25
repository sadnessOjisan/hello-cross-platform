# hello-cross-platform

```sh
cargo install cross

# build可能一覧
rustc --print target-list

# win向け
cross build --target x86_64-pc-windows-gnu

# mac向け
cross build --target x86_64-apple-darwin

# linux向け
cross build --target x86_64-unknown-linux-gnu
```

## memo

クロスコンパイルされたバイナリを実行するには QEMU
=> いまは実行はしないから使わない

cargo build --target <another architecture>ができるのがゴール．
