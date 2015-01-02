# Dropbox上にgitリポジトリを設置する

いくつかの手順が必要

## Dropbox内にベアリポジトリを作成

```bash
cd ~/Dropbox/git #Dropboxのフォルダ内にgitというフォルダがある場合
mkdir repository.git
cd repository.git
git --bare init
```

ref) [ベアリポジトリ](../repository/bare.md)

## Dropboxフォルダ以外の場所にリポジトリを作成\

```bash
#~ /gitフォルダ内にリポジトリを作成
mkdir ~/git/repository
cd ~/git/repository
git init
git add .
git commit -m "Initial commit"
```

## Dropbox内のリポジトリへpush

```bash
git remote add origin ~/Dropbox/git/repository.git
git push origin master
```


## 参考

* [version control - Using Git and Dropbox together effectively? - Stack Overflow](http://stackoverflow.com/questions/1960799/using-git-and-dropbox-together-effectively)
* [Dropbox内にgitのリポジトリを作る - 拡張現実ライフ](http://akio0911.net/archives/3289)

