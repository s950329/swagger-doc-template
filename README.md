<p align="center">
    <b>Special thanks to the generous sponsorship by:</b>
    <br><br>
    <a href="https://www.hourmasters.com">
      <img src="https://trello-attachments.s3.amazonaws.com/58a52a5cba3fdf7e02fe0b46/5a5ca9636a152015ebcddf8c/fd59154d52b5593b6082d96466694f73/slogan-01.png" width=350>
    </a>
</p>

# 鐘點大師 Swagger 文件撰寫模板

## 專案概述
專案名稱：鐘點大師 Swagger 文件撰寫模板

專案代號：doc-template

這是一個用來快速建構 Swagger 文件的模板，整合 Swagger UI 及 NPM 套件，可於編輯時即時預覽文件，並於編寫完畢立即交付。
另外也需注意，文件撰寫需組建化，將 `paths` 及 `schemas` 依業務邏輯分離，再以 `$ref` 的方式引入，詳見範例

## 功能如下
* 編寫文件，並即時預覽
* 編寫完畢即為可交付狀態文件

## 運行環境要求
* Node

## 安裝

### 基礎安裝
1. 克隆源碼

    > git clone https://github.com/s950329/swagger-doc-template.git

2. 安裝套件

    > npm install

3. 運行專案

    > npm run doc

### 整合至現有專案
1. 克隆源碼

    > git clone https://github.com/s950329/swagger-doc-template.git

2. 將 `package.json` 中的 `live-server` 套件及 `doc` 指令整合至現有專案的 `package.json`

3. 安裝套件

    > npm install

4. 運行專案

    > npm run doc
