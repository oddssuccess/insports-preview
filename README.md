# InSports 分享資料

InSports 對外分享與交付的資料，以 GitHub Pages 發布：<https://oddssuccess.github.io/insports-preview/>

本 repo 是公開的，放進來的內容任何人都看得到。

## 目錄

| 目錄 | 內容 | 維護方式 |
|------|------|----------|
| `wireframes/` | 後台畫面示意（wireframe） | 由 insports repo 的 `publish-preview` workflow 自動同步，請勿直接修改 |
| `diagrams/` | PRD 概念圖 | 同上 |
| 其他 | 首頁、本說明，以及之後人工放入的資料 | 人工維護 |

- 自動同步的兩個目錄會整個覆蓋，在本 repo 直接修改的內容會在下次同步時消失；要修改請改 insports repo 的 `docs/wireframes/` 或 `docs/diagrams/`。
- 新增其他資料時，另開目錄，並在首頁 `index.html` 加上連結。
- 頁面中連到 PRD 與 README 的連結指向私有的 insports repo，需要存取權限才能開啟。
