# Software Parts

## 1.Overview
テストコードやサンプルコードを管理するリポジトリである．

こういった「システムの部品」を蓄積することで，システム作りの際に「部品を組み合わせる」だけで済み，開発の効率が上がることを期待している．

このリポジトリには，動作するプログラムのみpushすることを許可する．

## 2.Directory 

ディレクトリ構造を以下に示す．
```
.
├── arduino
├── other
├── raspberrypi
└── stm
```

## 3.Branch
必ず"develop"ブランチから各自の名前の名前のブランチを作成し（```$ git branch```），管理する．
ブランチ名は利用者が容易に特定できるものであれば，本名でもニックネームでも何でも良い．

**Example**

```
user@MacBook:~/workspace/software-parts$ git branch
  master
  develop
* hashimoto
```