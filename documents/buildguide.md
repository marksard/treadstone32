# Build guide (ビルドガイド)

## The kit includes (キット内容)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|Treadstone32 PCB|1|The keyboard PCB|
|-|Treadstone32 Plate|1|FR4 Switch Plate|
|MSW1|TVBP06-B043CB|1|MCU Reset Switch|
|MSW2|TVBP06-B043CB|1|MCU Boot0 Switch|
|-|Treadstone32 Case|1||

## What needs to be purchased separately (choose your favorite) (キットに含まれません)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|MX Switches|32|As you like|
|-|Keycap set|-|As you like|
|RGB101-105|YS-SK6812MINI-E|5|As you like|

## Installation

1. Place the two tact switches (TVBP06-B043CB) on the side marked NRST and BOOT0 on the PCB and solder them together.
1. Insert the switches into the plate at the four end positions. Rotate the switches to the positions indicated by the red frames to install them.
1. Overlap the plate and PCB, taking care that the pins of the switch are not bent or oriented incorrectly.
1. Attach the remaining switches to the plate, taking care that the pins of the switches are not bent or oriented incorrectly.
1. Connect to the PC and confirm that it is recognized.

---

1. ２つのタクトスイッチ（TVBP06-B043CB）をPCBのNRST、BOOT0と書かれたほうに載せてハンダ付けしてください。（はめ込むだけでも一応使えます）
1. プレートにスイッチを端4か所差し込みます。赤い枠の位置はスイッチを回転して取り付けます。
1. スイッチのピンが曲がっていないか、向きが間違っていないか注意して、プレートとPCBを重ねてください。
1. スイッチのピンが曲がっていないか、向きが間違っていないか注意して、残りのスイッチをプレートに取り付けてください。
1. PCと接続し、認識されることを確認してください。

---

*1.*  
![IMGP8188]()

*2.*  
![IMGP8192]()


## Edit the keymap

Remap-compatible firmware has already been written to this PCB.  
You can change the keymap by accessing the following URL.  

以下のURLにアクセスし、キーマップを変更出来ます。  

[remap](https://remap-keys.app/)

## Firmware binary file

You can update the firmware by accessing the following URL.  
Usually it will not be necessary to do so.  

以下のURLにアクセスし、最新のファームウェアをアップデート出来ます。通常はそれを行う必要はないでしょう。  

[firmware](https://remap-keys.app/catalog/lVp2yaV5VNl1xikIcUGL/firmware)

## Bootloader Mode

### Method 1 (方法その1)

While pressing down the Escape key, connect to the PC.  
Escapeキーを押下しながら、PCと接続します。  


### Method 2 (方法その2)

Connect the keyboard to the PC and operate the tact switch attached to the keyboard in the following order:

1. Hold down the BOOT0 button and press the NRST button.  
2. Release the NRST button, then release the BOOT0 button.  

ＰＣにキーボードを接続し、キーボードに取り付けたタクトスイッチを以下の順に操作します。

1. BOOT0ボタンを押したまま、NRSTボタンを押します。
2. NRSTボタンを離してから、BOOT0ボタンを離します。

## If you need help

Twitter: @marksard
Discord: marksard