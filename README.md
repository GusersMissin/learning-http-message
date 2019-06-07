# HTTPでやりとりする仕組み

<!-- Markdown記法のヒント

コード記法（1行の中に埋めたい場合）

`code`

コードブロック記法（複数行）

```
print('a')
print('b')
```

-->

## 実習でやったこと (Y)

HTTPメッセージを見ること

## 自分で調べたこと

ない

## HTTPメッセージ (kd.txt) のうち、最も重要だと思う部分を貼り付けてください

```
SSL-Session:
    Protocol  : TLSv1.2
    Cipher    : ECDHE-RSA-AES256-GCM-SHA384
    Session-ID: C033C7E1C0E001653D25039243C2D13A262D76523952A4FAB5E2416C40871683
    Session-ID-ctx: 
    Master-Key: 969CED637A1C84607D320EE4BE9CCD916B28F70823493BA913AD3DFEF675E4ECF0A9D0784FB6637A30E65031337A051B
    PSK identity: None
    PSK identity hint: None
    SRP username: None
    TLS session ticket lifetime hint: 300 (seconds)
    TLS session ticket:
    0000 - fb 8b bd b5 c9 3c cd 5f-67 ba 54 d6 33 1b 97 96   .....<._g.T.3...
    0010 - bc db ab f7 56 9c d2 61-72 8b 64 bd 8d 32 cf ac   ....V..ar.d..2..
    0020 - f6 69 41 58 1b 98 04 b9-28 89 ef b3 9a e4 57 1f   .iAX....(.....W.
    0030 - b5 6f a3 40 ce fe 3e 11-7a e7 67 0e 20 b0 c9 73   .o.@..>.z.g. ..s
    0040 - a1 d4 6d 15 fa 82 dd e0-be ad ca 89 b9 97 ce cd   ..m.............
    0050 - 46 3e 2d eb dd e0 57 c6-76 cc 49 25 e8 65 d5 1b   F>-...W.v.I%.e..
    0060 - a0 e0 b4 a2 cd 5c 02 f3-38 ec 62 1b 88 d0 42 c1   .....\..8.b...B.
    0070 - f9 e0 bb 37 8d 34 e4 8f-a4 32 b4 e1 5b 7f f7 72   ...7.4...2..[..r
    0080 - 25 90 cf 4a 1f 8b 09 c2-10 d1 82 27 b8 b4 ba 09   %..J.......'....
    0090 - 4c 1b 89 58 d2 11 62 ca-82 58 e2 4c 96 57 3a f3   L..X..b..X.L.W:.
    00a0 - 53 86 37 72 59 e6 17 85-9f 9e f0 df 54 94 e9 64   S.7rY.......T..d
    00b0 - 13 40 c6 65 e4 ad 79 13-09 20 d3 13 7b 3b 48 af   .@.e..y.. ..{;H.
    00c0 - 15 05 91 4e 32 73 e5 89-b2 77 a6 27 3a 94 9d aa   ...N2s...w.':...

    Start Time: 1559874995
    Timeout   : 7200 (sec)
    Verify return code: 0 (ok)
    Extended master secret: no
---

Server: Apache
```

## それはなぜですか？

セキュリティ的で重要な部分だと思って
あと、使っているサーバーの種類を公開されたら
もしウェブをハッキングしようとする人あったらその人に情報になるんだと思うから

## わかったこと・気づいたこと

以外に色んなウェブがセキュリティ的に弱いかも知らないということ