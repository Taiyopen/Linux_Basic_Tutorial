# Linux Terminal 終端機
## 簡介
終端機（Terminal）是一種命令列介面（Command-Line Interface, CLI），簡單說就是一個提供使用者輸入指令的工具，讓使用者能訪問操作系統，像是文件管理、軟體安裝、系統環境變數設置等功能。

[CLI vs GUI](https://phoenixnap.com/kb/cli-vs-gui)


## 使用方法
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd>：開啟一個新的終端機
# 常用指令

## 目錄類

```bash
# 查看當前資料夾檔案
ls

# 切換資料夾
cd [資料夾名稱]
cd ..           # 回 上一層
cd              # 回 家目錄

# 創建資料夾
mkdir [資料夾名稱]
```

## 檔案類

```bash
# 刪除
rm [檔案名]      # 刪除檔案
rm -r [資料夾名] # 刪除資料夾
rm -rf [資料夾名] # "強制"刪除資料夾 (有些檔案有保護，刪不掉的話可以打這行)

# 複製
cp [檔案名] [資料夾] # 將檔案複製到指定資料夾
cp -r [資料夾a] [資料夾b] #將資料夾a 複製到資料夾b  

# 移動
mv [檔案名] [資料夾] # 將檔案移動到指定資料夾
mv -r [資料夾a] [資料夾b] #將資料夾a 移動到資料夾b 
```

## Sudo
(Superuser DO) 超級使用者權限。類似Windows的「以管理員身分執行」一樣。 通常須與其他指令（程式）一同使用（以管理員身份執行特定程式），請小心使用
```bash
user@my_computer_name:~$ sudo ${PROGRAM_NAME} 
#${PROGRAM_NAME} 可替代為其他指令 ex. mv, rm, apt-get ...
```

## 推薦

鳥哥私房菜 :<https://linux.vbird.org/linux_basic_train/centos8/>