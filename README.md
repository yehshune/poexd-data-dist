# poexd-data-dist

[PoeXD-Extension](https://github.com/yehshune/PoeXD-Extension) 使用的已發布遊戲資料。

Published game data for [PoeXD-Extension](https://github.com/yehshune/PoeXD-Extension).

## 內容

- 資料在 `gh-pages` 分支，由 CI 自動部署；`main` 只有這份說明。
- `manifest.json` 列出每個檔案的 sha256、大小、所屬批次與格式版本，擴充的 `pnpm data:sync` 依此驗證後才寫入。
- `version.json` 記錄資料對應的 PoE 1 / PoE 2 patch。

## 版權與聲明

- 遊戲文字、數值與圖示取自 Grinding Gear Games 的遊戲檔案與官方市集 API，版權屬於 Grinding Gear Games。本 repo 不對這些資料授予任何權利。
- 本專案與 Grinding Gear Games 無關，也未獲其背書。

Game text, values and icons come from Grinding Gear Games' game files and official trade API and remain their property; no rights to them are granted here. This project is not affiliated with or endorsed by Grinding Gear Games.
