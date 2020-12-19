# Visual Studio Code C++ 安裝教學
## 1. <a href="https://code.visualstudio.com/">安裝Visual Studio Code</a><br>
<img src="/image/VSCode下載頁面.png" width="400px"><br>

## 2. <a href="https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/installer/mingw-w64-install.exe/download">下載MinGW-w64</a><br>
<img src="/image/MinGW下載頁面.png" width="400px"><br>

## 3. 安裝MinGW-w64<br>
1. 打開下載的MinGW-w64<br>
<img src="/image/MinGW下載教學01.png" width="400px"><br>
2. 更改Architecture<br>
    * `32位元：i686`<br>
    * `64位元：x86_64`<br>
* <img src="/image/MinGW下載教學02.png" width="400px"><br>
3. 更改路徑為 ***C:\Mingw64*** `方便後續作業`<br>
<img src="/image/MinGW下載教學03.png" width="400px"><br>

## 4. 安裝Visual Stduio Code裡的**C/C++**<br>
<img src="/image/VSCode C++安裝教學.png" width="400px"><br>

## 5. 建構環境<br>
1. 打開**File Explorer**`檔案總管`<br>
    * 右鍵**This PC**`我的電腦`<br>
    * 左鍵**Properties**`內容`<br>
* <img src="/image/環境建構教學01.png" width="400px"><br>
2. 點擊**Advanced system settings**`進階系統設定`<br>
<img src="/image/環境建構教學02.png" width="400px"><br>
3. 點擊**Environment Variables**`環境設定`<br>
<img src="/image/環境建構教學03.png" width="300px"><br>
4. 點擊系統變數裡的**Path**`路境`，在點擊**Edit**`修改`<br>
<img src="/image/環境建構教學04.png" width="300px"><br>
5. 點擊**New**`新增`，輸入 ***C:\Mingw64\mingw64\bin*** `第三大步建立的位置`<br>
<img src="/image/環境建構教學05.png" width="300px"><br>
6. ***重啟Visual Studio Code***<br>