# Build guide (ビルドガイド)

## The kit includes (キット内容)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|M0ii040 PCB|1|The keyboard PC|
|-|M0ii040 Plate|1|FR4 Switch Plate|
|MSW1|TVBP06-B043CB|1|MCU Reset Switch|
|MSW2|TVBP06-B043CB|1|MCU Boot0 Switch|
|-|CPG15*|40|Kailh Switch Socket|

## What needs to be purchased separately (choose your favorite) (キットに含まれません)

|no|name|qty|description|
|:--|:--|:--|:--|
|-|M0ii0 Case|1|-|
|-|MX Switches|39 or 40|As you like (Treadstone layout is use 39)|
|-|Keycap set|-|As you like|
|-|Screw-in Stabies|2|As you like|

## Installation

1. Place the two tact switches (TVBP06-B043CB) on the side marked NRST and BOOT0 on the PCB and solder them together.
2. Insert the switches into the plate. The position of the red frame is installed by rotating the switch.
3. Install the screw-in stabilizer.Install the wire so that it is positioned at the back.
4. Overlap the plate with the switch and the PCB.
5. Carefully attach the socket to the pins of the switch coming out of the holes in the PCB. Make sure they are facing the right way.
6. Solder the socket to the PCB.
7. Connect to the PC and confirm that it is recognized.

---

1. ２つのタクトスイッチ（TVBP06-B043CB）をPCBのNRST、BOOT0と書かれたほうに載せて、ハンダ付けしてください。
1. プレートにスイッチを差し込みます。赤い枠の位置はスイッチを回転して取り付けます。
1. スクリューインスタビライザーを取り付けます。ワイヤーが奥に位置するように取り付けます。
1. スイッチをつけたプレートとPCBを重ねてください。
1. PCBの穴から出ているスイッチのピンに、注意深くソケットを取り付けます。向きを間違えないようにしてください。
1. ソケットとPCBをハンダ付けしてください。
1. PCと接続し、認識されることを確認してください。

---

*1.*  
![IMGP8188](https://user-images.githubusercontent.com/38324387/226540271-5ee768b5-dc0c-42b9-a1a4-333f33e1a05b.JPG)

*2.*  
![IMGP8192](https://user-images.githubusercontent.com/38324387/226543169-7d9786df-c998-47b1-841e-feb3e934f89f.JPG)

*3.*  
![IMGP8206](https://user-images.githubusercontent.com/38324387/226543202-dc2c6fc3-7a5b-4ec4-b689-c86b72224709.JPG)

*5.*  
![IMGP8185](https://user-images.githubusercontent.com/38324387/226543287-c17ea7c9-2386-49b7-aaf2-8f0f4c899f80.JPG)


## Edit the keymap

Remap-compatible firmware has already been written to this PCB.  
You can change the keymap by accessing the following URL.  

以下のURLにアクセスし、キーマップを変更出来ます。  

[remap](https://remap-keys.app/)

If you purchased the Treadstone layout, please change the layout below.  

Treadstoneレイアウトをご購入の場合は以下からレイアウトを変更してください。  

![スクリーンショット 2023-03-20 232012](https://user-images.githubusercontent.com/38324387/226368667-9098d496-a22b-426f-9da2-35a410a56275.png)

## Firmware binary file

You can update the firmware by accessing the following URL.  
Usually it will not be necessary to do so.  

以下のURLにアクセスし、最新のファームウェアをアップデート出来ます。通常はそれを行う必要はないでしょう。  

[firmware](https://remap-keys.app/catalog/AheP3WR8nb6M6Bj3pq9Q/firmware)

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
