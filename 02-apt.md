# APT

## APT簡介
Advanced Packaging Tools，縮寫為APT，是Debian及其衍生的Linux軟體包管理器。(取自維基)

簡單來說

就像是IOS平台的app store，Android平台的google play

多數軟體可以直接從APT下載下來，不必到各個網站下載

## 常用指令

因為安裝軟體大多會動到系統層，所以必須加上`sudo`

```bash
# 更新APT資訊與列表(可隨手打一下)
sudo apt update

# 更新所有軟體到最新版本(可隨手打一下)
sudo apt upgrade

# 安裝
sudo apt install [套件名]

# 解除安裝
sudo apt remove [套件名]

# 解除安裝並刪除設定檔
sudo apt purge [套件名]
```