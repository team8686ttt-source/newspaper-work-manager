# newspaper-work-manager
勤務表作成プロジェクト・新聞休刊日データ
## データ構成

| ファイル | 内容 |
|---------|------|
| `data/newspaper_holidays.json` | 新聞休刊日リスト（年別） |

## 利用方法

### raw URL（VBA等から取得）
https://raw.githubusercontent.com/team8686ttt-source/newspaper-work-manager/main/data/newspaper_holidays.json

### データ形式
- JSON形式、年ごとに日付配列
- 日付は `YYYY-MM-DD` 形式（ISO 8601）
- `note`: 「朝刊製作が休みとなる日」＝翌日が配達なし

## 今後の予定
- [ ] 勤務表自動生成機能
- [ ] Excel VBAからの自動取得マクロ
- [ ] 勤務シフトパターンデータ
