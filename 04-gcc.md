# GCC

**說明：為了幫助大家習慣linux，以簡易的執行一隻hello world讓大家練習**

* **Preprocessing**

  即將 #define 刪除，展開所有巨集。將所有 #include 的檔案插入。處理 #if/#ifdef 等的 conditional 指令。刪除所有註解。添加行號。preprocessing 完後會產生 .i 檔

* **Compiling**

  將預處理的檔案組譯成組合語言, 產生 .s 的檔案

* **Assembling**

  將組合語言變成機器碼 .o 的檔案

* **Linking**

  連接函式庫與其他檔案，產生可執行檔

* GCC on ubuntu

``` bash
gcc --version                    # 檢查gcc版本
sudo apt install build-essential # 下載ubuntu提供的編譯軟件包
```

### 1. Hello World

(1) 完整流程

編譯組譯生成 .o 檔

```bash
gcc -c hello.c
```

鍊結生成執行檔，並執行

``` bash
gcc -o hello hello.o
./hello
```

(2) 快速流程

```bash
gcc hello.c
./a.out
```

### 2. main + function
老師常說的拆function，在terminal也是可以的
``` bash
gcc -c main.c function.c
gcc -o '執行檔名稱' main.o function.o
./'執行檔名稱'
```
---

大家會發現平時使用的IDE為我們做了很多事，至於如何更進階的了解整合的過程，就可以學習cmake，雖然這有助於同學們更理解程式，但希望大家先理解就好，不用一定現在要學會使用cmake。

### 進階部份，請參考帥氣的繼群學長[CMake教學](https://gitlab.ical.tw/a1075144/cmake_practice) 

