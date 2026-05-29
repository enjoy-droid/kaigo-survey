# kaigo-survey / コンサルティング準備資料

複数の役割（**岡崎市議会議員・ケアマネジャー・居宅介護支援事業所管理者・経営者・産業ケアマネ**）を担うクライアントの「両立」を支援するコンサルティングのための準備一式です。

## 成果物一覧

| # | ファイル | 内容 | 用途 |
|---|---------|------|------|
| 1 | [`docs/01_consulting-proposal.md`](docs/01_consulting-proposal.md) | コンサルティング提案書／準備レポート | 全体設計・進め方の社内/対クライアント共有 |
| 2 | [`docs/02_presentation.md`](docs/02_presentation.md) | プレゼン資料（スライド・Marp形式） | キックオフ／提案プレゼン |
| 3 | [`docs/03_survey.md`](docs/03_survey.md) | アンケート設問・調査票 | 現状把握のためのサーベイ実施 |
| 4 | [`docs/04_meeting-prep.md`](docs/04_meeting-prep.md) | 初回面談ヒアリング設計・チェックリスト | 初回コンサル面談の準備 |

## このコンサルティングの狙い（要約）

クライアントは 5 つの顔を持っています。それぞれは独立して見えますが、「**地域の高齢者・働く介護者を支える**」という一本の軸でつながり得ます。本コンサルティングは、

1. 5 役割の**時間・役割・リスクを棚卸し**し、
2. 役割間の**シナジー**（特に *産業ケアマネ × 居宅 × 議員* の地域モデル）を設計し、
3. **両立を持続可能にする仕組み**（権限委譲・収益構造・KPI）を整える

ことをゴールとします。

## 想定する外部環境（要・最新確認）

- 2025年4月施行の **改正育児・介護休業法** により、企業に「仕事と介護の両立支援」措置が義務化 → 産業ケアマネの需要追い風。
- **ビジネスケアラー（働きながら介護する人）** の増加と介護離職による経済損失が政策課題化。

> ⚠️ 本資料中の統計・制度の数値は作成時点の一般知識に基づきます。提案前に必ず一次情報（厚労省・経産省・岡崎市資料等）で最新確認してください。該当箇所には「**[要確認]**」を付しています。

## スライドのプレビュー方法（Marp）

`docs/02_presentation.md` は [Marp](https://marp.app/) 記法です。

```bash
# VS Code 拡張「Marp for VS Code」を入れてプレビュー、または:
npx @marp-team/marp-cli docs/02_presentation.md -o presentation.pdf   # PDF
npx @marp-team/marp-cli docs/02_presentation.md -o presentation.html  # HTML
npx @marp-team/marp-cli docs/02_presentation.md --pptx -o presentation.pptx  # PowerPoint
```
