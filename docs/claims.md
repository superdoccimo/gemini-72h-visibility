# Claims vs Facts（主張と事実の線引き）

このリポジトリでは「事実」と「意見」を明確に分けています。

---

## Facts（公式根拠あり）

以下は Google の公式ドキュメントに記載されている内容です。

| 事実 | 出典 |
|------|------|
| Keep Activity OFF でも、会話は最大72時間保存され得る | [Gemini Help](https://support.google.com/gemini/answer/13278892?hl=en) |
| その短期保存は Gemini Apps Activity に表示されない | [Gemini Help](https://support.google.com/gemini/answer/13278892?hl=en) |
| 保持の目的はサービス提供・フィードバック処理等と説明されている | [Gemini Help](https://support.google.com/gemini/answer/13278892?hl=en) |
| 削除しても人手レビューに回ったデータは別枠で保持されうる | [Gemini Privacy Hub](https://support.google.com/gemini/answer/13594961?hl=en) |
| Workspace では顧客データをモデル学習に使わない旨が明記されている | [Workspace Privacy](https://support.google.com/a/answer/15706919?hl=en) |
| Google Cloud の Gemini もプロンプト/応答を学習に使わない旨がある | [Cloud Data Governance](https://docs.cloud.google.com/gemini/docs/discover/data-governance) |

---

## Opinions（意見・解釈）

以下はこのリポジトリの執筆者の見解です。異論はありえます。

- 「学習オフ」という言葉は「保存しない」と誤解されやすく、**ミスリード（誤認を誘う）になりうる UI / 文言** である
- 「見えない保持」は **透明性が低い** と感じるユーザーが多い
- プライバシーを優先すると履歴機能を失う設計は、**ユーザーに不利な二択を迫っている**
- 消費者向けと業務向けで扱いが異なることは、**情報の非対称性** を生んでいる
- この種の批判記事が Google 検索で不利になりうる構造は、**プラットフォーム支配の問題** と関連する

---

## この線引きが重要な理由

- **事実だけ**で攻めると、「書いてあるじゃん」で終わりやすい
- **意見だけ**で攻めると、「お気持ちでしょ」で片付けられやすい
- **事実＋意見を分けて提示**することで、読者が自分で判断できる
