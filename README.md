# auto-rccar-unimog

## はじめに

タミヤRCカー メルセデス ベンツ ウニモグ 406を自動で走らせるソフトです  

## 概要

ローカライゼーションはRTK-GNSSのみ  
ナビゲーションはNav2を使用  
方向検出や障害物検出にCameraのIMUやDepthを使用  
サーボはM5 ATOM Matrixでmicro-ROSを使用  
Googole My Mapsで設定した経路に沿って走ります

## Movie

<table>
<tr>
<td><img width="640" src=""></td>
</tr>
</table>

## Image

<table>
<tr>
<td><img width="320" src="https://github.com/endusers/auto-rccar-toy/blob/main/assets/image/DSC_0967.JPG"></td>
<td><img width="320" src="https://github.com/endusers/auto-rccar-toy/blob/main/assets/image/DSC_0969.JPG"></td>
</tr>
<tr>
<td><img width="320" src="https://github.com/endusers/auto-rccar-toy/blob/main/assets/image/DSC_0962.JPG"></td>
<td><img width="320" src="https://github.com/endusers/auto-rccar-toy/blob/main/assets/image/DSC_0966.JPG"></td>
</tr>
</table>

## ソフトウェア

| ソフト           | リンク |
| ---------------- | ------------------------------------------------------------------ |
| 自立走行ソフト   | [auto-rccar-toy](https://github.com/endusers/auto-rccar-toy)       |
| RCカー制御ソフト | [m5stack-rccar-toy](https://github.com/endusers/m5stack-rccar-toy) |
