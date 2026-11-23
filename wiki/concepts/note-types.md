# 基礎操作與四種音符（Note）

當音符與[動態判定線](./judgment-line.md)重合的瞬間，根據音符顏色與形狀執行對應手勢即可得分 `[來源: source_02]`。

## 四種音符對照表
| 音符名稱 | 外觀顏色 | 操作手勢 | 判定特性 |
| :--- | :--- | :--- | :--- |
| **Tap** | 藍鍵 | 單指點擊一下 | 具備 Perfect / Good / Bad / Miss 判定 `[來源: source_02]` |
| **Drag** | 黃鍵 | 手指按住停留接取即可 | 僅有 Perfect 與 Miss，不會斷連 `[來源: source_02]` |
| **Hold** | 藍白長條 | 頭部按下並持續按住至尾部 | 尾部判定較寬鬆 `[來源: source_02]` |
| **Flick** | 紅鍵 | 朝任意方向滑動一下 | 無方向限制，僅有 Perfect 與 Miss `[來源: source_02]` |

## 判定區間與多指操作
- 一般模式下，**Perfect 為 ±80ms**，**Good 為 ±160ms**（會扣減準度 ACC 但維持連擊 Combo），超出則為 Bad 或 Miss `[來源: source_02]`（若進入[課題模式](./progression-and-unlocks.md)，Perfect 區間會縮減一半）。
- 遊戲支援多指觸控，進階難度（如 IN、AT）常需三指至四指同時操作（多押） `[來源: source_02, source_04]`。
