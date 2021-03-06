# QtCompressor

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/94100e791d454c8790619a5e191a38a8)](https://www.codacy.com/app/WhatTheBlock/QtCompressor?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=WhatTheBlock/QtCompressor&amp;utm_campaign=Badge_Grade)

## 介紹

#### 這是一個整合各CLI壓縮工具的視窗程式

#### 目前共整合以下8款

1. WinRAR
2. 7-Zip
3. UPX
4. Paq8pxd
5. Paq8px
6. cmix
7. BCM
8. Kanzi

UI介面：
----
![ui.png](/ui.png)

## 編譯方式

#### 使用Qt 5.13.0以上版本開啟專案編譯即可

## 已知問題

1. 7-Zip、UPX功能尚未編寫
2. 其他工具解壓功能尚未編寫

## Changelog

[Link](https://whattheblock.github.io/)

## 注意事項

1. 為了支援大檔案壓縮，壓縮工具都使用64位元版本
2. 測試區所整合的壓縮工具需占用大量的記憶體空間
3. Paq8系列、BCM和Kanzi壓縮工具有修改部分源碼，包含壓縮檔的檔案標頭和輸出字串中文化
4. 為了減少檔案大小，所有整合的壓縮工具皆使用UPX進行加殼壓縮
