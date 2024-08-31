# TextBitDumper
入力された文字列のビット列をDumpするWebアプリ

## 機能
- 入力された文字列を指定された文字コードで解釈する
  + Shift_JIS
  + UTF-8
  + UTF-16 LE
- 指定文字コードでのビット列を8bitごとに出力
  + 区切り文字を指定可能
    * カンマ+スペース (CS)
    * カンマ (Comma)
    * スペース (Space)
    * 改行 (LF)
    * なし (None)
  + 出力時の基数を指定可能
    * 2 (BIN)
    * 8 (OCT)
    * 10 (DEC)
    * 16 (HEX)
  + 接頭辞をつけることが可能
    * 0b (2)
    * 0o  (8)
    * 0x (16)
- そのビット列を他の文字コードで解釈したものを出力
- クエリパラメータ(str=???)で文字列を事前入力可能
  * [https://mr-ojii.github.io/TextBitDumper?str=こんにちは](https://mr-ojii.github.io/TextBitDumper?str=こんにちは)
