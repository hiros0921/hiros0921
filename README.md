## 諏訪 裕之 — Hiroyuki Suwa

株式会社LIGHTECH 代表取締役。2001年からシステム開発と業務改善に従事しています。

システムを**作る側**（開発・保守・設計）と、**毎日使う側**（物流の現場実務）の両方を、
同じ11年半のなかで担当しました。仕様どおり動いているのに現場が回らない、という状況を
何度も見てきたので、「動くもの」ではなく「使い続けられるもの」を作ります。

近年は生成AIを実務に組み込む設計に取り組んでいます。関心があるのは
「AIで何ができるか」よりも、**AIの出力をどうやって機械で検収するか**の方です。
生成AIは黙って失敗します。音声は漢字を読み違え、画像は真っ黒なまま返り、
動画は1フレームも動かないことがある。人が全部見て気づくのは無理なので、
出力を測って判定する仕組みを先に作ります。

### 主なもの

| | |
|---|---|
| **[lecture-factory](https://github.com/hiros0921/lecture-factory)** | 生成AIの出力を機械で検収してから使うパイプライン。合成音声を波形と文字起こしで照合し、誤読・尻切れ・無音を自動検出して作り直す。撮影ゼロで26本・計28分の動画講義を約700円で制作 |
| **[memory-fragments](https://github.com/hiros0921/memory-fragments)** | 感情とともに日々を記録する日記アプリ。Stripe決済・Firebase認証・IndexedDBによるオフライン保存。→ [www.memory-fragments.com](https://www.memory-fragments.com) |
| **[teshigotoya](https://github.com/hiros0921/teshigotoya)** | AI文章の仕上げサービス。静的サイト＋Netlify Functions によるフォーム受付・自動返信 → [teshigotoya.jp](https://teshigotoya.jp) |

### 作ったもの（コードは非公開）

- [教材・講座の構成設計AI](https://brain-creator.vercel.app) — テーマから章立て・特典・価格設計までを生成。サーバーレス関数で入力検証を実装
- [試作7件](https://lightech-works.netlify.app) — 文章分析・構成支援などの試作。ブラウザ内で完結
- [夜咲くGarden / Hiro](https://www.youtube.com/watch?v=fVj974Kgcqg) — 生成AIで制作した60秒のミュージックビデオ。明るさと動き量を測って不良カットを自動検出

### 使うもの

| | |
|---|---|
| **近年** | Python・JavaScript・TypeScript・SQL ／ Firebase・Stripe・Netlify・Cloudflare Workers・Vercel ／ ffmpeg |
| **以前** | Java・C++・Visual Basic・Oracle（2001〜2012年　業務システムの開発・保守） |

### そのほか

慶應義塾大学 法学部 卒 ／ 応用情報技術者 ／ TOEIC 990点

書いたもの → [Substack](https://substack.com/@hirosuwa)

polygonplanet/encoding.js #64   マージ済み
duckdb/duckdb-encodings #19     調査が upstream の修正に取り込まれた
mholt/PapaParse                 2件
ggml-org/whisper.cpp            2件

### OSSへの貢献
- [polygonplanet/encoding.js #64](https://github.com/polygonplanet/encoding.js/pull/64) — 文字コード判定の誤検出を修正（マージ済・v2.3.0で動作確認）
- [duckdb/duckdb-encodings #19](https://github.com/duckdb/duckdb-encodings/issues/19) — CP932の変換不備を調査。upstream の修正 #20 に反映

- 
