Proxmox VE 使用者手冊
=
> 此份文件為使用者所撰寫，非官方文件

## Proxmox VE 簡介
Proxmox VE 是一個開放原始碼的虛擬化環境，基於 Debian Linux 所開發，支援「虛擬機」(Kernel-based Virtual Machine)、「Linux 軟體容器」(Linux Containers)，Proxmox VE 包含：網頁控制台、命令列工具，且提供 REST API 功能以串接第三方程式。

此文件為大家共同撰寫，歡迎大家共同修改編輯，以降低導入 Proxmox VE 的導入難度，共同邁向 OpenSource 的美好~。 

## 目錄
- [系統安裝](doc/01.installation.md)
    - [行前準備](doc/01.installation.md#行前準備)
    - [開始安裝-初階版](doc/01.installation.md#開始安裝-初階版)
    - [開始安裝-進階版](doc/01.installation.md#開始安裝-進階版)

- 首要設定
    - 防火牆設定
    - 新增管理帳號，關閉 root 之 SSH 權限
    - Let's Encrypt 憑證安裝
