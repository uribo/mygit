# ベアリポジトリ

```bash
mkdir test.git
cd test.git
git init --bare
```

慣習的にベアリポジトリにはフォルダ名に`.git`を付ける。

## ベアリポジトリの中身

ベアリポジトリの構造は通常のリポジトリとは異なっている。

```bash
ls -a
#.           HEAD        description info        refs
#..          config      hooks       objects
```
