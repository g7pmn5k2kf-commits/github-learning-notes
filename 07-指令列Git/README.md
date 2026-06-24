# 07 - 指令列 Git 基礎

## 什麼是指令列

指令列（Terminal）是用鍵盤打文字指令來操作電腦，不需要點按鈕。
比網頁介面更強大，可以做到很多網頁做不到的事。

本章使用 GitHub Codespaces，在瀏覽器裡直接操作指令列，不需要在電腦安裝任何東西。

---

## 開啟 Codespaces

1. 在 GitHub repo 頁面點綠色 `Code` 按鈕
2. 點 `Codespaces` 標籤
3. 點 `Create codespace on main`
4. 等待載入完成後，點下方「終端機」標籤

---

## 基本導覽指令

| 指令 | 功能 | 範例 |
|------|------|------|
| `ls` | 列出目前資料夾的內容 | `ls` |
| `cd 資料夾名稱` | 進入某個資料夾 | `cd 07-指令列Git` |
| `cd ..` | 回到上一層資料夾 | `cd ..` |

注意：`cd` 和 `..` 之間一定要有空格，`cd..` 會出現錯誤。

---

## git status

查看目前 Git 的狀態，是最常用的指令。

    git status

三種常見的回應：

- `nothing to commit, working tree clean` — 目前沒有任何修改
- `Untracked files` — 有新檔案，Git 還沒追蹤
- `Changes to be committed` — 檔案已加入暫存區，準備 Commit

---

## 指令列 Git 核心流程

Git 的 Commit 分兩個步驟：

第一步：git add（把檔案放進箱子）
第二步：git commit（把箱子封起來）
第三步：git push（把箱子寄出去到 GitHub）

---

## 完整指令對照表

| 指令 | 功能 |
|------|------|
| `git status` | 查看目前狀態 |
| `git add 檔案名稱` | 把指定檔案加入暫存區 |
| `git add .` | 把所有修改過的檔案加入暫存區 |
| `git commit -m "說明"` | 建立 Commit，說明寫在引號裡 |
| `git push` | 推送到 GitHub 網站 |
| `git rm 檔案名稱` | 刪除檔案並記錄這次刪除 |

---

## 檔案狀態說明

左邊檔案列表旁邊的字母代表不同狀態：

| 字母 | 說明 |
|------|------|
| U | Untracked，新檔案，Git 還沒追蹤 |
| A | Added，已加入暫存區 |
| M | Modified，已修改但還沒 add |

---

## 今天完成的操作

- [x] 開啟 GitHub Codespaces
- [x] 學會 ls、cd、cd .. 基本導覽指令
- [x] 用 git status 查看狀態
- [x] 用指令建立新檔案
- [x] 完整走完 git add → git commit → git push 流程
- [x] 用 git rm 刪除檔案並推送

---

*學習日期：2026-06-24*
