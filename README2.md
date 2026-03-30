



① プロジェクト概要（最初に一文＋箇条書き）

「ZANDAKA は、現在の残高・今月あとどれだけ使えるかを“パッと”把握できる個人向け家計アプリです。」
その下に3〜5行で要約：
今いくら使っているか
今月あとどれだけ使えるか
今後入る収入・出ていく支出予定
将来はレシート読み取り（OCR）も予定、など
② 主要機能（Features）

収入/支出の登録（カテゴリ・メモ付き）
月ごとの一覧・フィルタ
月のサマリ（支出合計・残り使える額）
予算/見込み収入の設定
予定機能（認証・レシートOCR・ユーザー分離 など）
③ 技術スタック（Tech Stack）

フロント：Next.js（React）
バックエンド：Java + Spring Boot (REST API)
DB：PostgreSQL (Docker)
その他：Docker / Prisma 相当のORMを使うならその名前 / テストフレームワーク など
→ 「Javaもフロントも書ける人」をアピールできる欄。
④ アーキテクチャ概要（System Architecture）

シンプルな説明：
Next.js → Spring Boot REST API → Postgres の3層
できれば簡単な図（テキストでもOK）：
Browser → Next.js → Spring Boot API → DB