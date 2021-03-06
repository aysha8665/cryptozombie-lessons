---
title: "コントラクト"
actions: ['答え合わせ', 'ヒント']
material: 
  editor:
    language: sol
    startingCode: |
      pragma solidity //　1. solidityのバージョンをここに入力するのだ

      //　2. ここにコントラクトを作成するのだ
    answer: > 
      pragma solidity ^0.4.19;


      contract ZombieFactory {

      }
---

一番簡単なことから始めよう：

Solidityのコードは**コントラクト**内にカプセル化されている。`コントラクト`はイーサリアムアプリケーションの基本ブロックのことだ。変数やファンクションはすべてコントラクトに属している。これがプロジェクトの出発点になる。

`HelloWorld`という名前の空のコントラクトはこういう形で表現される：

```
contract HelloWorld {

}
```

## Version pragma(バージョンのプラグマ)

Solidityのソースコードは全て”version pragma"で始まらなければならない。コードが使用するSolidityのコンパイラのバージョンを宣言するものだ。これは、将来コンパイラのバージョンが原因でコードが壊れることを防ぐために必要なのだ。

実際には`pragma solidity ^0.4.19;` という風に宣言する（この解説を書いている時点での最新のsolidityのバージョンは0.4.19)。

これをまとめれば、コントラクトを開始するための骨組みが出来上がる　ー 新しいプロジェクトを始める毎に毎回必ず書くことを忘れるなよ：


```
pragma solidity ^0.4.19;

contract HelloWorld {

}
```

# テストの実行

ゾンビ軍団を生み出すための、`ZombieFactory`というコントラクトを作成してみよ。

1. 右のボックス内に、solidity `0.4.19`バージョンを指定して、コントラクトを使う準備をせよ

2. `ZombieFactory`という空のコントラクトを作成せよ

作成が終わったら、下の"答え合わせ"をクリックせよ。もし迷うことがあれば、"ヒント"を押せばヒントをやろう。 
