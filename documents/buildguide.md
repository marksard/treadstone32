# Build guide (ビルドガイド)

## The kit includes (キット内容)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|Treadstone32 PCB|1|The keyboard PCB|
|-|Treadstone32 Plate|1|FR4 Switch Plate|
|MSW1|TVBP06-B043CB|1|MCU Reset Switch|
|MSW2|TVBP06-B043CB|1|MCU Boot0 Switch|
|-|Treadstone32 Case|1||
|-|M2 4mm|4||
|-|Rubber Feet|4||

## What needs to be purchased separately (choose your favorite) (キットに含まれません)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|MX Switches|32|As you like|
|-|Keycap set|-|As you like|
|RGB101-105|YS-SK6812MINI-E|5|As you like|

## Installation

1. Place the two tact switches (TVBP06-B043CB) on the PCB side of the photo, in the yellow frame, on the side marked NRST and BOOT0 on the PCB and solder them. (It is possible to use it even if you just fit it in.)
1. The head of the switch will appear in the yellow frame on the side of the plate in the photo, so align the plate with that orientation.
1. Insert the switch into the plate in the four places on the edge. Note that the direction of the switch in the red frame is different from the other parts.
1. Insert the switch into the socket, overlapping the plate and PCB, making sure that the switch pins are not bent or oriented incorrectly.
1. Install the remaining switches onto the plate and into the socket, taking care that the pins of the switches are not bent and that they are not oriented incorrectly.
1. Connect to the PC and verify that it is recognized.
1. If it seems to be interfering with the case, shave off the green part a little and attach it to the case with M2 screws.
1. Attach the rubber feet to the case.

---

1. 写真のPCB側、黄色枠に２つのタクトスイッチ（TVBP06-B043CB）をPCBのNRST、BOOT0と書かれたほうに載せてハンダ付けしてください。（はめ込むだけでも一応使えます）
1. 写真のプレート側、黄色枠にスイッチの頭がでますので、プレートをその向きに合わせます。
1. プレートにスイッチを端の4か所に差し込みます。赤い枠部分はスイッチの向きがほかと違いますので注意してください。
1. スイッチのピンが曲がっていないか、向きが間違っていないか注意して、プレートとPCBを重ねてソケットに差し込んでください。
1. スイッチのピンが曲がっていないか、向きが間違っていないか注意して、残りのスイッチをプレートとソケットに取り付けてください。
1. PCと接続し、認識されることを確認してください。
1. ケースに干渉しているようであれば、緑の箇所を少し削って、M2ネジでケースに取り付けてください。
1. ラバーの足をケースにとりつけてください。

---

![20240229_IMGP8666](https://github.com/marksard/treadstone32/assets/38324387/5618aec6-a447-43d0-a865-5f0afc436d6b)

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
