# RubyScope
スコープの理解

## 処理
変数の有効範囲を理解するため、それぞれに変数`a`を定義して確認する。

## コード
```
def sum(x, y)
    a = 5
    puts "変数aは#{a}です。"
    return x + y
end

a = 10
b = 20
gokei = sum(a, b)
puts "変数aは#{a}です。"
puts "変数bは#{b}です。"
puts "合計は#{gokei}です。"
```

## 出力結果  
```
変数aは5です。
変数aは10です。
変数bは20です。
合計は30です。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
