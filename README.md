# LANDNAX

PasocomMini(PC-8001)用シューティングゲーム  
月刊マイコン , 電波新聞社, 1989年 4月号掲載  

## How to execute
1. /PCM に ファイル landnax, landnax_m_all を保存して、Pasocom mini(PC-8001) を起動する
2. [F9] を押し、MEDIA タブで landnax_m_all を set する
3. mon [Enter]
4. L [Enter]
5. CTRL + B でマシン語入力モードを抜ける
6. [F9] を押し、MEDIA タブで landnax を set する
7. CLOAD "landnax" [Enter]
8. run

## Files
landnax: N-BASIC プログラム (起動用)  
landnax_m_all: マシン語プログラム (全部)
/files/landnax_m1: マシン語プログラム (A000-A7EF)  
/files/landnax_m2: マシン語プログラム (B500-C28E)  
/files/landnax_m3: マシン語プログラム (9000-9852)  
/files/landnax_m4: マシン語データ (B000-B3A7)  
/files/landnax_m5: マシン語データ (C400-C5C8)  
/files/landnax_m6: マシン語データ (D000-DD85)  
/files/checksum: N-BASIC プログラム (入力チェック用)  

## ゲームパッド設定
[F9] を押し、GAMEPAD タブで下記を設定する

[2]: DOWN (デフォルト設定)  
[8]: UP (デフォルト設定)  
[4]: LEFT (デフォルト設定)  
[6]: RIGHT (デフォルト設定)  
[SPACE]: 1, 3ボタン (デフォルト設定)  
[SHIFT]: 2, 4ボタン (アイテム切り替え用)  
[RETURN]: 12ボタン (ゲーム開始用)  
[ESC]: 11ボタン (一時停止用)  

(参考)  
https://www.pcmini.jp/manual/pc-8001-manual/pc-8001-stting/gamepad/
