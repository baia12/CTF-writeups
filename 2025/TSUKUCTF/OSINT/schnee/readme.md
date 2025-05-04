<p align="center">
  <img src="schnee.jpg" alt="Alt text" width="500"/>
</p>


>素敵な雪山に辿り着いた！スノーボードをレンタルをして、いざ滑走！
>フラグフォーマットは写真の場所の座標の小数点第4位を四捨五入して、小数第3位まで>をTsukuCTF25{緯度_経度}の形式で記載してください。
>例: TsukuCTF25{12.345_123.456}

## Translation:
I’ve felt the power.

The flag format is TsukuCTF25{latitude_longitude} of the location where this person is standing. Note that the latitude and longitude are rounded down to five decimal places.

## Solution:

Looking at the image, it is tactile map of someplace in Japan( as the image contains a japanese character). It contains a braille etched metal plate.

Used Google lens on the image,it provide location the mountain at grindelwald. I notice the banner write *buri Sport* After that
I use google maps and search Buri Sport Grindelwald and got multi branch.looking outside the branch and found the similar place. Got the coordinated, rounded them.

I got the flag! hohohoh

## Flag:
```
TsukuCTF25{46.623_8.039}
```
