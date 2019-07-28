# ファームウェアについて

# ファームウェアの場所
QMK Firmware本家へまだmergeされていません。
以下のリポジトリからcloneしてください。

https://github.com/hsgw/qmk_firmware/tree/tartan

## QMK Firmwareのセットアップ
- https://github.com/qmk/qmk_firmware
- https://docs.qmk.fm/#/newbs_getting_started

## デフォルトキーマップのビルドと書き込み
ターミナルでQMK Firmwareにディレクトリに移動して

#### ファームウェアのビルドのみ
```
make tartan:default
```

#### ビルドしてPlaidへ書き込む
Tartanをブートローダモードにしてから
```
make tartan:default:program
```

## ジャンパー線でテスト
デフォルトキーマップを初めて書き込んだあと、キースイッチをはんだづけする前に適当なジャンパー線、抵抗の足で実際にタイプ出来るかテストするのをオススメします。

## キーマップのカスタマイズ
- https://docs.qmk.fm/#/newbs_building_firmware

## ファームウェアを改良したら
Send PR!

## NEXT
[スイッチのはんだづけとボトムPCBの取り付け](./complete.md)