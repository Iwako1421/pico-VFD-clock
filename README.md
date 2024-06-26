# pico-VFD-clock
simple VFD clock using raspberry pi pico

## 部品表
|基板上の表記|値・部品番号|秋月電子通販コード(旧)|
|:----|:----|:----|
|C1|4.7u|P-08154|
|C2|0.33u|P-08147|
|C3|0.33u|P-08147|
|C4|4.7u|P-08154|
|C5|4.7u|P-08154|
|C6|4.7u|P-08154|
|C7|0.1u|P-15927|
|C8|0.1u|P-15927|
|C9|0.1u|P-15927|
|SW1|SET|P-03647|
|SW2|ADJ|P-03647|
|U1|MAX662|I-01165|
|U2|Raspberry Pi Pico|M-16132|
|U3|UT7500L-25-T92-B-K|I-10268|
|U4|TBD62783A|I-10957|
|U5|TBD62783A|I-10957|
|U6|TBD62783A|I-10957|
|U7|LD8195|付属(名古屋大須・ボントンで入手)|

## 組み立て方
1. 部品表を見ながら部品をはんだ付けします
2. このgithubリポジトリ (https://github.com/Iwako1421/pico-VFD-clock) をzipでダウンロードし、解凍してprogram/VFDclock.uf2を取り出します
3. raspberry pi picoのbootselボタンを押しながらmicroUSBケーブルでPCと接続します
4. raspberry pi picoがストレージとして認識されるので、そこにVFDclock.uf2をドラッグ&ドロップします
5. 時刻を合わせて完成

## 時刻合わせ方法
ADJキーを押すたびに通常表示→時間合わせ→分合わせ→秒合わせ→12時制/24時制切り替え→通常表示と切り替わります。合わせたい項目のモードにADJキーで切り替えて、SETキーを押して調整した後ADJキーで通常表示に戻ってください。

## 電源について
USB-MicroBケーブルで給電してください。コネクタが外れやすいので、ケーブルを抜くときは大きくこじらずにまっすぐ引き抜いてください。

## 注意
VFDはガラス製です。割れやすい (特に突起部分) ので、落としたりぶつけたりしないよう十分ご注意ください。

## 質問等
制作者Twitter (@iwamechatronics) またはEmail (k_iwakura1421@outlook.jp) までご連絡ください。
