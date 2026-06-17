# 04 - 分支與 PR

## 為什麼需要分支

main 是正在使用的穩定版本，不能直接在上面實驗。
分支讓你可以在獨立的空間修改、測試，沒問題才合併回 main。

---

## 分支的運作方式

    main    ●────────────────────────●
                  ↘                 ↗
    新分支          ●────●────●

main 一直存在，新分支從某個點分出去，做完再合併回來。
main 完全不受影響。

---

## 建立分支的步驟

1. 在 Repo 主頁點 main 下拉選單
2. 在搜尋框輸入新分支名稱
3. 點「Create branch」建立

---

## 在分支上修改

切換到新分支後，所有的修改只會影響這條分支。
切回 main，分支上的修改完全看不到。

---

## Pull Request（PR）是什麼

PR 是「我想把這條分支的內容合併回 main」的申請。

流程：
1. 在分支上完成修改
2. GitHub 自動偵測到分支有新內容，顯示黃色提示列
3. 點「Compare & pull request」
4. 填寫 PR 標題，說明這次做了什麼
5. 點「Create pull request」
6. 確認沒問題後點「Merge pull request」合併

---

## PR 頁面的重要資訊

- Able to merge：兩條分支可以順利合併，沒有衝突
- Commits：這個 PR 包含哪些 Commit
- Files changed：這個 PR 改了哪些檔案
- No conflicts with base branch：可以安全合併

---

## 合併後的清理

合併完成後，GitHub 會提示「Delete branch」。
分支的工作已完成、內容已進入 main，可以刪除分支。

---

## 重要觀念

- main 永遠是穩定可用的版本
- 所有實驗和修改都在分支上進行
- 分支經過測試沒問題，才合併回 main
- 合併後刪除分支是標準的清理動作

---

## 今天完成的操作

- [x] 建立 practice-edit 分支
- [x] 在分支上修改 README.md
- [x] 發 Pull Request
- [x] 合併分支回 main
- [x] 刪除已合併的分支

---

*學習日期：2026-06-16*
