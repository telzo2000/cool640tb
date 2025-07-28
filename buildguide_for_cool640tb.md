 　# Buildguide for cool640tb
<br>


## 0 部品の確認
<br>
Follow the BOM on github's readme.md to make sure that all the parts are available.
<br>
githubのreadme.mdのBOMに沿って、部品が全て揃っているかを確認してください。
<br>


## 1 ダイオードのはんだ付け

If the diode is already soldered, please skip this operation.
<br>
すでにダイオードのはんだ付けされている場合は、この作業を省略してください。
<br>
<br>
This work is done on the left and right keyboard boards respectively.
<br>
この作業は左右のキーボード基板でそれぞれ行います。
<br> 
Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
As expected, it is compatible with SMD type.
<br>
ダイオードは、SMDタイプに対応しています。
<br>
Diodes have polarity, so be careful about the direction in which they are installed.
<br>
ダイオードには極性がありますので、取り付ける向きに注意してください。
<br>

[ダイオード（SMD)のはんだ付けの動画](https://youtu.be/ODk16bd4XkA)
<br>
[ダイオード（リードタイプ）のはんだ付けの動画](https://youtu.be/lbAQkKzNawM)
<br>
[ダイオード（リードタイプ）のはんだ付けの動画２](https://youtu.be/3hWZjaBROL8)

<br>

## 2  スイッチソケットのハンダ付け

cool640tb supports choc switch sockets.
<br>
cool640tbでは、chocのスイッチソケットに対応しています。
<br><br>
Solder the switch socket to the back of the keyboard board.
<br>
キーボード基板の裏面にスイッチソケットのハンダ付けをします。
<br>

[Switch socketハンダ付け動画](https://youtu.be/ZnbgaueMR4w?si=_JLjD--3HJJ5Pu7Q)


<br>

## 3 Seeed xiao ble Plus(xiao nRF 52840 Plus)のハンダ付け

<b>Note</b>
<br>
次の動画を参考にしてハンダ付けをしてください。
<br>
[xiao ble Plusのハンダ付け動画](https://youtu.be/T4O7NxNUMdo)



## 4  電池ボックス取り付け


Insert the battery box from the bottom of the board and temporarily fix it in place with masking tape. Then, cut off the leads sticking out from the top of the board with pliers or something similar, and solder them.
<br>
電池ボックスを基板の下面から、差し込み、マスキングテープで仮固定します。そして、基板の上面から飛び出したリードをニッパーなどで切り取り、ハンダ付けをしてください。
<br>

## 5 スライドスイッチのハンダ付け

Insert the switch from the underside of the PCB with the tab facing outwards.
<br>
スイッチのつまみが外側に向くようにして、PCBの下面から差し込みます。
<br>
Temporarily fix it in place with masking tape or something similar, then cut off the part sticking out on the top surface of the PCB with pliers, and then solder it.
<br>
マスキングテープなどで仮固定をしてから、PCBの上面に出た部分をニッパーで切り取ってから、はんだ付けします。
<br>


[スライドスイッチのはんだ付けの作業動画](https://youtu.be/5nkRklibay4)

<br>

## 6 リセットスイッチのハンダ付け

The switch button faces down and is inserted into the underside of the PCB.
<br>
スイッチのボタンが下に向くようにして、 PCBの下面から差し込みます。
<br>
Temporarily fix it in place with masking tape or something similar, then cut off the part sticking out on the top surface of the PCB with pliers, and then solder it.
<br>
マスキングテープなどで仮固定をしてから、PCBの上面に出た部分をニッパーで切り取ってから、はんだ付けします。


[リセットスイッチハンダ付け動画](https://youtu.be/Pl24Exfh8b8)

## 7 トラックボール基板の作成

Caution PMW3610 is prone to sensor damage when exposed to high temperature heat. Please complete the soldering of each pin in a short time.
<br>
注意　PMW3610は高温の熱にさらされるとセンサーの破損が発生しやすいです。それぞれのピンのはんだ付けは短時間で済ませてください。
<br>
As for my example, soldering is processed in 2-3 seconds per pin.
<br>
私の例ですが、はんだ付けを１つのピンにつき、2〜3秒で処理します。
<br>
<br>
Note: The silk of "Front side" and "Back side" on the board is written for the ball.
<br>
注意　基板に「Front side」や「Back side」のシルクは、ボールに対しての表記です。
<br>
<br>
The trackball board has components installed from the beginning. The implemented side is the back side.
<br>
トラックボール基板は最初から部品が実装されています。実装されている面を裏面とします。
<br>
<br>
Remove the PWM3610 acrylic parts.
<br>
PWM3610アクリル部品を取り外します。
<br>
<br>
Check the pin of the PMW3610 and insert it from the surface of the trackball board. Temporarily fix it with masking tape.
<br>
PMW3610のピンを確認して、トラックボール基板の表面から差し込みます。マスキングテープで仮固定します。

![](img/img00004.jpg)

<br>
<br>
The back of the trackball board is facing up and the part that came out of the pin hole is soldered.
<br>
トラックボール基板の裏面を上向きにして、ピン穴からでた部分をはんだ付けします。
<br>
<br>
The lens part of the PMW3610 is covered with tape, so remove it.
<br>
PMW3610のレンズ部分がテープで覆われているので、それを外します。
<br>
<br>
From the back of the trackball board, cover the acrylic part on the PMW3610, and melt the acrylic on the back with a soldering ick to prevent it from coming off.
<br>
トラックボール基板の裏面の方から、アクリル部品をPMW3610に被せて、その裏側に出たアクリルをハンダごてで溶かして外れないようにします。

![](img/img00005.jpg)
<br>
<br>

## 8 センサー基板のはんだ付け

The sensor board created in step 7 is fixed to the circuit board by soldering it with the pin head in between.
<br>
7で作成したセンサー基板を基板にピンヘッドを間に挟んではんだ付けして固定します。
<br>

![](img/img00006.jpg)

Please refer to the diagram above when soldering. When doing so, use pliers or similar to cut off any protruding pin heads.
<br>
上の図を参考にして、はんだ付けをしてください。その際、はみ出たピンヘッドはニッパーなどで切り取ってください。
<br>


## 9 スペーサーの装着

Insert the M2 3mm screw from the top of the board and secure it with the M2 6mm spacer from the bottom of the board.
<br>
基板の上面から、M2 3mmネジを挿入して、基板の下面からM2 6mmスペーサーで固定してください。
<br>
This is done in four places.
<br>
これは４箇所行います。
<br>


## 10　キースイッチの装着

Insert the key switch in the following order: top case, then PCB.
<br>
トップケース、PCBの順になるように、キースイッチを差し込んでください。
<br>
When inserting the key switch, make sure the pins are straight.
<br>
キースイッチを差し込む時、キースイッチのピンが真っ直ぐになっているか、確認してください。
<br>

## 11 トラックボールの装着

Place the 12mm POM ball in the designated location on the top case.
<br>
12mmPOM球をトップケースの所定の位置に装着してください。
<br>

![](img/img00007.jpg)


## 12 動作確認について

ファームウェアの導入について、こちらの記事を参考にしてください。
<br>
[自作キーボードへのzmk_firmwareのインストールについて](https://sizu.me/m_ki/posts/kvixkn2mec6a)



<br>
Keymapの編集について、こちらの記事を参考にしてください。

[zmk_firmwareでのキーマップ編集について](https://sizu.me/m_ki/posts/m3devs7be5km)



## 9 ボトムケースの装着

動画を参考にしてください。

[ケースの開閉について](https://www.youtube.com/watch?v=Rq6qG2JvAKY)


##  10　キーキャップの装着

Please attach your favorite keycap.
<br>
お好きなキーキャップを装着してください。
<br>


## 11 完成

After attaching non-slip rubber to the bottom of the bottom case, it's done.
<br>
Please enjoy a life with a better keyboard.
<br>
ボトムケースの底面に、滑り止めゴムを取り付けたら、完成です。
<br>
よりよいキーボードのある生活を楽しんでください。
<br>

![](img/img00001.jpg)



