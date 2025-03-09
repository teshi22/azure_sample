# Azure OpenAI Serviceモデル


## [アーティクル]·2025/02/28

Azure OpenAl Service では、さまざまな機能と価格ポイントを備えた多様なモデルセットが利用されています。モデルの可用性はリージ
ョンとクラウドごとに異なります。Azure Government モデルの可用性については、Azure Government の OpenAl Service に関するセク
ションを参照してください。

〔〕 テーブルを展開する


<table>
<tr>
<th>モデル</th>
<th>説明</th>
</tr>
<tr>
<td>○ シリーズ モデル</td>
<td>高度な問題解決、増強された集中力と能力を備えた推論モデル。</td>
</tr>
<tr>
<td>GPT-4o、GPT-4o mini、GPT- 4 Turbo</td>
<td>最新の最も能力の高い Azure OpenAl モデルであり、テキストと画像の両方を入力として受け入れることができるマルチ モーダル バージョンを備えています。</td>
</tr>
<tr>
<td>GPT-4o audio</td>
<td>低遅延、"音声入力、音声出力" の会話のやり取り、またはオーディオ生成をサポートする GPT-4o audio モデル。</td>
</tr>
<tr>
<td>GPT-4</td>
<td>GPT-3.5 を基に改善され、自然言語とコードを理解し、生成できるモデルのセット。</td>
</tr>
<tr>
<td>GPT-3.5</td>
<td>GPT-3 を基に改善され、自然言語とコードを理解し、生成できるモデルのセット。</td>
</tr>
<tr>
<td>埋め込み</td>
<td>テキストを数値ベクトル形式に変換して、テキストの類似性を促進できるモデルのセット。</td>
</tr>
<tr>
<td>DALL-E</td>
<td>自然言語からオリジナルの画像を生成できるモデルのシリーズ。</td>
</tr>
<tr>
<td>Whisper</td>
<td>音声を文字起こしして音声テキスト変換を翻訳できる一連のモデル。</td>
</tr>
<tr>
<td>テキスト読み上げ(プレビュ ) ー</td>
<td>テキストを音声に合成できるプレビュー段階の一連のモデル。</td>
</tr>
</table>


### ○ シリーズ モデル

Azure OpenAl の o *シリーズ モデルは、集中と能力を高めて推論と問題解決のタスクに取り組むために特に設計されています。これら
のモデルは、ユーザーの要求の処理と理解により多くの時間を費やし、これまでのイテレーションと比較して、科学、コーディング、数
学などの分野で非常に強力になっています。

〔〕 テーブルを展開する


<table>
<tr>
<th>モデル ID</th>
<th>説明</th>
<th>最大要求(トー クン)</th>
<th>トレーニング デ ータ(最大)</th>
</tr>
<tr>
<td>o3-mini (2025- 01-31)</td>
<td>最新の推論モデルであり、推論能力が強化されています。 - 構造化出力 - テキストのみの処理 - 機能/ツール アクセスの要求: 制限付きアクセス モデルの申請</td>
<td>入力:200,000 出力:100,000</td>
<td>2023年10月</td>
</tr>
<tr>
<td>o1 (2024-12-17)</td>
<td>01 シリーズの中で最も能力の高いモデルで、推論能力が強化されています。 - 構造化出力 - テキスト、画像処理 - 機能/ツール アクセスの要求: 制限付きアクセス モデルの申請</td>
<td>入力:200,000 出力:100,000</td>
<td>2023年10月</td>
</tr>
<tr>
<td>o1-preview (2024-09-12)</td>
<td>以前のプレビュー バージョン</td>
<td>入力:128,000 出力:32,768</td>
<td>2023年10月</td>
</tr>
<tr>
<td>o1-mini (2024- 09-12)</td>
<td>01 シリーズの中のより速く、よりコスト効率の高いオプションであり、速度を必要としリソー ス消費を削減する必要があるコーディング タスクに最適です。 グローバル標準デプロイが既定で使用できるようになりました。 現在、標準(リージョン)のデプロイは、o1-preview の制限付きアクセス リリースの一部として アクセス権を付与されたお客様のみが利用できます。</td>
<td>入力:128,000 出力:65,536</td>
<td>2023年10月</td>
</tr>
</table>


可用性

<!-- PageBreak -->

o3-miniとo1にアクセスするには、登録が必要であり、Microsoftの適格性条件に基づいてアクセスが許可されます。以前にo1-
preview または 01 へのアクセスを申請して受け取ったお客様は、○ シリーズの最新モデルの待機リストに自動的に追加されるため、再申
請する必要はありません。

アクセスの要求: 制限付きアクセス モデルの申請

アクセス権が付与されたら、モデルごとにデプロイを作成する必要があります。

高度な o-series モデルの詳細については、「推論モデルの概要」を参照してください。


## 利用可能なリージョン

〔〕 テーブルを展開する


<table>
<tr>
<td>モデル</td>
<td>リージョン</td>
</tr>
<tr>
<td>o3-mini</td>
<td>「モデル テーブル」を参照してください。</td>
</tr>
<tr>
<td>o1</td>
<td>「モデル テーブル」を参照してください。</td>
</tr>
<tr>
<td>o1- preview</td>
<td>「モデル テーブル」を参照してください。このモデルを使用できるのは、元の制限付きアクセスの一部としてアクセス権を付与されたお客 様に限られます</td>
</tr>
<tr>
<td>o1-mini</td>
<td>「モデル テーブル」を参照してください。</td>
</tr>
</table>


# GPT-4o audio

GPT 4o audio モデルは GPT-40 モデル ファミリの一部であり、低遅延の“音声入力、音声出力" の会話のやり取りまたはオーディオ生成
のいずれかをサポートします。

● GPT-4o real-time audio は、リアルタイムで低待機時間の会話を処理するように設計されており、サポート エージェント、アシスタ
ント、翻訳者、およびユーザーとの応答性の高いやり取りを必要とするその他のユース ケースに最適です。GPT-40 real-time audio
の使用方法の詳細については、GPT-4o real-time audio のクイックスタートおよび GPT-40 audio の使用方法を参照してください。

● GPT-4o audio completion は、オーディオまたはテキスト プロンプトからオーディオを生成するように設計されており、オーディオ
ブックやオーディオ コンテンツの生成、およびオーディオ生成を必要とするその他のユース ケースに最適です。GPT-40 audio
completion モデルでは、既存の /chat/completions API にオーディオ モダリティが導入されています。GPT-4o audio completion の
使用方法の詳細については、 audio 生成のクイックスタートを参照してください。

GPT-4o audio を使用するには、いずれかのサポートされているリージョンの Azure OpenAl リソースが必要です。

リソースが作成されたら、GPT-4o audio モデルをデプロイできます。

次の表では、最大要求トークン数とトレーニング データに関する詳細を確認できます。

〔〕 テーブルを展開する


<table>
<tr>
<th>モデル ID</th>
<th>説明</th>
<th>最大要求(トーク ン)</th>
<th>トレーニング データ(最 大)</th>
</tr>
<tr>
<td>gpt-4o-mini-audio-preview (2024-12-17) GPT-4o audio</td>
<td>オーディオとテキスト生成向けのオーディオ モデル。</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年10月</td>
</tr>
<tr>
<td>gpt-4o-mini-realtime-preview (2024-12- 17) GPT-4o audio</td>
<td>リアルタイム オーディオ処理向けのオーディオ モデ ル。</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年10月</td>
</tr>
<tr>
<td>gpt-4o-audio-preview (2024-12-17) GPT-4o audio</td>
<td>オーディオとテキスト生成向けのオーディオ モデル。</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年10月</td>
</tr>
<tr>
<td>gpt-4o-realtime-preview (2024-12-17) GPT-4o audio</td>
<td>リアルタイム オーディオ処理向けのオーディオ モデ ル。</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年10月</td>
</tr>
<tr>
<td>gpt-4o-realtime-preview (2024-10-01) GPT-4o audio</td>
<td>リアルタイム オーディオ処理向けのオーディオ モデ ル。</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年10月</td>
</tr>
</table>


利用可能なリージョン

<!-- PageBreak -->

<!-- PageHeader="〔〕 テーブルを展開する" -->


<table>
<tr>
<td>モデル</td>
<td>リージョン</td>
</tr>
<tr>
<td>gpt-4o-mini-audio-preview</td>
<td>米国東部 2 (グローバル標準)</td>
</tr>
<tr>
<td>gpt-4o-mini-realtime-preview</td>
<td>米国東部 2 (グローバル標準) スウェーデン中部(グローバル標準)</td>
</tr>
<tr>
<td>gpt-4o-audio-preview</td>
<td>米国東部 2 (グローバル標準) スウェーデン中部(グローバル標準)</td>
</tr>
<tr>
<td>gpt-4o-realtime-preview</td>
<td>米国東部 2(グローバル標準) スウェーデン中部(グローバル標準)</td>
</tr>
</table>


すべてのリージョンで GPT-40 audio モデルの可用性を比較するには、モデルの表を参照してください。


# GPT-4oおよびGPT-4 Turbo

GPT-4oは、テキストと画像を1つのモデルに統合し、複数のデータ型を同時に処理できるようにします。このマルチモーダルアプロー
チにより、人間とコンピューターの対話における精度と応答性が向上します。GPT-40 は、英語以外の言語とビジョン タスクで優れたパ
フォーマンスを提供しながら、英語のテキストとコーディング タスクにおいて GPT-4 Turbo に匹敵し、AI 機能の新しいベンチマークを
設定します。


# GPT-40 と GPT-40 mini のモデルにアクセスする方法

GPT-40 と GPT-40 mini は、Standard と Global-Standard のモデル デプロイで利用できます。

このモデルを利用できる サポート対象の標準リージョンまたはグローバル標準リージョンに、新しいリソースを作成するか既存のリソー
スを使用する必要があります。

リソースの作成が済んだ後、GPT-40 モデルをデプロイできます。プログラムでデプロイを実行する場合、モデルの名前は次のとおりで
す。

● gpt-40 バージョン 2024-11-20

● gpt-40 バージョン 2024-08-06

● gpt-40 バージョン 2024-05-13

● gpt-40-mini バージョン 2024-07-18


# GPT-4 Turbo

GPT-4 Turbo は、大規模なマルチモーダル モデル(テキストまたは画像の入力を受け入れ、テキストを生成します) であり、OpenAl の以
前のモデルよりも高い精度で困難な問題を解決できます。 GPT-3.5 Turbo や以前の GPT-4 モデルと同様に、GPT-4 Turbo はチャット用に
最適化されており、従来の入力候補タスクでも適切に動作します。

GPT-4 Turbo の最新の GA リリースは次のとおりです。

● gpt-4 バージョン turbo-2024-04-09

これは、次のプレビュー モデルに代わるものです。

● gpt-4 バージョン1106-Preview

● gpt-4 バージョン 0125-Preview

● gpt-4 バージョンvision-preview


# OpenAIとAzure OpenAI GPT-4 Turbo GAモデルの違い

● OpenAl の最新の 0409 ターボ モデル バージョンでは、すべての推論要求に対して JSON モードと関数呼び出しがサポートされてい
ます。

● Azure OpenAl の最新の turbo-2024-04-09 バージョンでは、現在、画像(ビジョン)入力による推論要求を行う場合、JSON モードと
関数呼び出しの使用はサポートされていません。テキスト ベース入力の要求(image_url とインライン イメージがない要求)では、
JSON モードと関数呼び出しがサポートされています。

<!-- PageBreak -->


# gpt-4 vision-preview との違い

● Azure Al 固有の Vision 拡張機能と GPT-4 Turbo with Vision の統合は、gpt-4 バージョン: turbo-2024-04-09 ではサポートされませ
ん。これには、光学式文字認識 (OCR)、オブジェクト グラウンディング、ビデオ プロンプト、画像を含むデータの処理の改善が含
まれます。


## 1 重要

光学式文字認識 (OCR)、オブジェクト グラウンディング、ビデオ プロンプトなどのビジョン拡張機能のプレビュー機能は廃止され、
gpt-4 バージョン: vision-preview が turbo-2024-04-09 にアップグレードされると使用できなくなります。現在これらのプレビュー
機能のいずれかに依存している場合、このモデルの自動アップグレードは破壊的変更になります。


# GPT-4 Turbo のプロビジョニングされたマネージド可用性

● gpt-4 バージョン turbo-2024-04-09 は、標準デプロイとプロビジョニングされたデプロイの両方で使用できます。現在、このモデ
ルのプロビジョニングされたバージョンでは、イメージ/ビジョン推論要求はサポートされていません。このモデルのプロビジョニ
ングされたデプロイでは、テキスト入力のみ受け入れます。標準のモデル デプロイでは、テキストと画像/ビジョンの両方の推論要
求を受け入れます。


# GPT-4 Turbo with Vision GA のデプロイ

Azure AI FoundryポータルからGAモデルをデプロイするには、GPT-4を選択し、ドロップダウンメニューからturbo-2024-04-09バージ
ョンを選択します。 gpt-4-turbo-2024-04-09 モデルの既定のクォータは、GPT-4-Turbo の現在のクォータと同じになります。リージョン
別のクォータ制限を参照してください。


## GPT-4

GPT-4 は、GPT-4 Turbo の前身です。GPT-4 と GPT-4 Turbo のどちらのモデルも、基本モデル名は gpt-4 です。 モデルのバージョンを
調べると、GPT-4 モデルと Turbo モデルを区別できます。

● gpt-4 バージョン 0314

● gpt-4 バージョン 0613

● gpt-4-32k バージョン 0613

各モデルでサポートされているトークン コンテキストの長さは、モデルの概要テーブルで確認できます。


# GPT-4 モデルと GPT-4 Turbo モデル

● これらのモデルは Chat Completion API でのみ使用できます。

モデル バージョンを参照して、Azure OpenAl Service がモデル バージョンのアップグレードを処理する方法と、モデルを使用して GPT-4
デプロイのモデル バージョン設定を表示および構成する方法について説明します。

に テーブルを展開する


<table>
<tr>
<th>モデル ID</th>
<th>説明</th>
<th>最大要求(トー クン)</th>
<th>トレーニング デー タ(最大)</th>
</tr>
<tr>
<td rowspan="3">gpt-4o (2024-11-20) GPT-4o (Omni)</td>
<td>最新の大きい GA モデル</td>
<td>入力:128,000</td>
<td>2023年10月</td>
</tr>
<tr>
<td rowspan="2">- 構造化出力 - テキスト、画像処理 - JSON モード - 並列関数呼び出し - 精度と応答性の向上 - GPT-4 Turbo with Vision と比較した英語のテキストおよびコーディング タスクの 同等性 - 英語以外の言語とビジョン タスクでの優れたパフォーマンス。 - クリエイティブ ライティング能力の向上</td>
<td rowspan="2">出力:16,384</td>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td>gpt-4o (2024-08-06)</td>
<td>- 構造化出力</td>
<td>入力:128,000</td>
<td>2023年10月</td>
</tr>
<tr>
<td>GPT-4o (Omni)</td>
<td>- テキスト、画像処理 - JSON モード - 並列関数呼び出し</td>
<td>出力:16,384</td>
<td></td>
</tr>
</table>


<!-- PageBreak -->


<table>
<tr>
<th>モデル ID</th>
<th>説明</th>
<th>最大要求(トー クン)</th>
<th>トレーニング デー タ(最大)</th>
</tr>
<tr>
<td></td>
<td>- 精度と応答性の向上 - GPT-4 Turbo with Vision と比較した英語のテキストおよびコーディング タスクの 同等性 - 英語以外の言語とビジョン タスクでの優れたパフォーマンス</td>
<td></td>
<td></td>
</tr>
<tr>
<td>gpt-4o-mini (2024-07-18) GPT-4o mini</td>
<td>最新の小さい GA モデル - GPT-3.5 Turbo シリーズのモデルを置き換えるのに最適な、高速で安価で高機能の モデル。 - テキスト、画像処理 - JSON モード - 並列関数呼び出し</td>
<td>入力:128,000 出力:16,384</td>
<td>2023年10月</td>
</tr>
<tr>
<td>gpt-4o (2024-05-13) GPT-4o (Omni)</td>
<td>テキスト、画像処理 - JSON モード - 並列関数呼び出し - 精度と応答性の向上 - GPT-4 Turbo with Vision と比較した英語のテキストおよびコーディング タスクの 同等性 - 英語以外の言語とビジョン タスクでの優れたパフォーマンス</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年10月</td>
</tr>
<tr>
<td>gpt-4 (turbo-2024-04-09) GPT-4 Turbo with Vision</td>
<td>新しい GA モデル - 以前のすべての GPT-4 プレビュー モデル(vision-preview、1106-Preview、0125- Preview) についての代替モデル。 現在 、- 機能の使用の可否は、入力方法とデプロイの種類によって異なります。</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年12月</td>
</tr>
<tr>
<td>gpt-4 (0125-Preview)* GPT-4 Turbo プレビュー</td>
<td>プレビュー モデル - 1106-Preview に代わるものです - コード生成パフォーマンスが向上 - モデルがタスクを完了しないケースを減らします。 - JSON モード - 並列関数呼び出し - 再現可能な出力(プレビュー)</td>
<td>入力:128,000 出力:4,096</td>
<td>2023年12月</td>
</tr>
<tr>
<td>gpt-4 (vision-preview) GPT-4 Turbo with Vision Preview</td>
<td>プレビュー モデル - テキストと画像の入力を受け入れます。 - 機能強化に対応します - JSON モード - 並列関数呼び出し - 再現可能な出力(プレビュー)</td>
<td>入力:128,000 出力:4,096</td>
<td>2023 年4月</td>
</tr>
<tr>
<td>gpt-4 (1106-Preview) GPT-4 Turbo プレビュー</td>
<td>プレビュー モデル - JSON モード - 並列関数呼び出し - 再現可能な出力(プレビュー)</td>
<td>入力:128,000 出力:4,096</td>
<td>2023 年4月</td>
</tr>
<tr>
<td>gpt-4-32k (0613)</td>
<td>古い GA モデル ー ツールによる基本的な関数呼び出し</td>
<td>32,768</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-4 (0613)</td>
<td>古い GA モデル ー ツールによる基本的な関数呼び出し</td>
<td>8,192</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-4-32k (0314)</td>
<td>古い GA モデル - 廃止に関する情報</td>
<td>32,768</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-4 (0314)</td>
<td>古い GA モデル - 廃止に関する情報</td>
<td>8,192</td>
<td>2021 年9月</td>
</tr>
</table>


## ♡ 注意事項

運用環境でプレビュー モデルを使用することはおすすめしません。プレビュー モデルのすべてのデプロイは、将来のプレビューバ
ージョンか最新の安定GAバージョンにアップグレードされます。プレビューに指定されたモデルは、標準のAzure OpenAIモデル
のライフサイクルに従っていません。

● GPT-4 バージョン 0125-preview は、以前にバージョン 1106-preview としてリリースされた GPT-4 Turbo プレビューの更新バージ
ョンです。

● GPT-4 バージョン 0125-preview は、gpt-4-1106-preview と比較して、コード生成などのタスクをより完全に完了します。このた
め、タスクによっては、GPT-4-0125-preview が gpt-4-1106-preview と比較してより多くの出力を生成することがあります。お客様
には、新しいモデルの出力を比較することをお勧めします。GPT-4-0125-preview では、英語以外の言語の UTF-8 処理に関する gpt-
4-1106-preview のバグにも対処しています。

<!-- PageBreak -->

● GPT-4 バージョン turbo-2024-04-09 は最新の GA リリースであり、0125-Preview、1106-preview、vision-preview に代わるもので
す。


# GPT-3.5

GPT-3.5 モデルは、自然言語とコードを理解および生成できます。GPT-3.5 ファミリで最も能力とコスト効率の高いモデルは GPT-3.5
Turbo です。これはチャット用に最適化されており、従来の補完タスクでも適切に動作します。GPT-3.5 Turbo は、Chat Completions API
で使用できます。GPT-3.5 Turbo Instruct には、Chat Completions API の代わりに Completions API を使用する text-davinci-003 のと同
様の機能があります。GPT-3.5 および GPT-3 のレガシ モデルよりも GPT-3.5 Turbo および GPT-3.5 Turbo Instruct を使用することをお勧
めします。

〔〕 テーブルを展開する


<table>
<tr>
<th>モデル ID</th>
<th>説明</th>
<th>最大要求(トーク ン)</th>
<th>トレーニング データ (最大)</th>
</tr>
<tr>
<td>gpt-35-turbo (0125) 新規</td>
<td>最新の GA モデル - JSON モード - 並列関数呼び出し - 再現可能な出力(プレビュー) - 要求された形式での応答精度の向上。 - 英語以外の言語の関数呼び出しに対してテキスト エンコードの問題が発生して いたバグの修正。</td>
<td>入力:16,385 出力:4,096</td>
<td>2021 年9月</td>
</tr>
<tr>
<td rowspan="2">gpt-35-turbo (1106)</td>
<td>古い GA モデル</td>
<td>入力:16,385</td>
<td rowspan="2">2021 年9月</td>
</tr>
<tr>
<td>- JSON モード - 並列関数呼び出し - 再現可能な出力(プレビュー)</td>
<td>出力:4,096</td>
</tr>
<tr>
<td>gpt-35-turbo-instruct (0914)</td>
<td>入力候補エンドポイントのみ - レガシ補完モデルの置き換え</td>
<td>4,097</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-35-turbo-16k (0613)</td>
<td>古い GA モデル - ツールによる基本的な関数呼び出し</td>
<td>16,384</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-35-turbo (0613)</td>
<td>古い GA モデル ー ツールによる基本的な関数呼び出し</td>
<td>4,096</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-35-turbo 1 (0301)</td>
<td>古い GA モデル - 廃止に関する情報</td>
<td>4,096</td>
<td>2021 年9月</td>
</tr>
</table>


GPT-3.5 Turbo と Chat Completions API の使用方法について詳しくは、詳細なハウツーをご覧ください。

1 このモデルは、> 4096 個のトークン要求を受け入れます。モデルの新しいバージョンは 4,096 個のトークンに制限されるため、4,096
個の入力トークンの制限を超えないようにすることをお勧めします。このモデルで 4,096 個の入力トークンを超えたときに問題が発生し
た場合、この構成は公式にはサポートされていません。


# 埋め込み

text-embedding-3-large は、最新かつ最も高性能の埋め込みモデルです。埋め込みモデル間でアップグレードすることはできません。
text-embedding-ada-002 の使用から text-embedding-3-large の使用に移行するには、新しい埋め込みを生成する必要があります。

· text-embedding-3-large

. text-embedding-3-small

· text-embedding-ada-002

OpenAl の報告によると、テストでは、大規模と小規模の第3 世代埋め込みモデルのいずれも、MIRACL ベンチマークで多言語検索の平
均パフォーマンスが向上しており、さらに MTEB ベンチマークで英語タスクのパフォーマンスを維持しています。

〔〕 テーブルを展開する


<table>
<tr>
<th>評価ベンチマーク</th>
<th>text-embedding-ada-002</th>
<th>text-embedding-3-small</th>
<th>text-embedding-3-large</th>
</tr>
<tr>
<td>MIRACL 平均</td>
<td>31.4</td>
<td>44.0</td>
<td>54.9</td>
</tr>
<tr>
<td>MTEB 平均</td>
<td>61.0</td>
<td>62.3</td>
<td>64.6</td>
</tr>
</table>


<!-- PageBreak -->

第3世代の埋め込みモデルは、新しい dimensions パラメーターを使った埋め込みのサイズ削減をサポートしています。通常、埋め込み
が大きくなると、コンピューティング、メモリ、ストレージの観点からコストが高くなります。ディメンション数を調整できるので、全
体的なコストとパフォーマンスをより詳細に制御できます。dimensionsパラメーターはOpenAI 1.x Pythonライブラリのすべてのバージ
ョンでサポートされているわけではありません。このパラメーターを利用するには、最新バージョンの pip install openai -- upgrade に
アップグレードすることをお勧めします。

OpenAIのMTEBベンチマークテストにより、第3世代モデルのディメンションは、text-embeddings-ada-002 1,536ディメンション未満
に減らした場合でも、パフォーマンスはわずかに優れていることがわかりました。


# DALL-E

DALL-E モデルは、ユーザーが提供するテキスト プロンプトから画像を生成します。 DALL-E 3 は、REST API との併用で一般提供されてい
ます。クライアント SDK を使用する DALL-E 2 と DALL-E 3 は、プレビュー段階です。


# Whisper

Whisper モデルは、音声テキスト変換に使用できます。

Azure Al Speech バッチ文字起こし API を使用して、ささやきモデルを使用することもできます。Azure Al 音声と Azure OpenAl Service
の使い分けの詳細については、「Whisper モデルとは」を参照してください。


# テキスト読み上げ(プレビュー)

現在プレビュー段階にある OpenAl テキスト読み上げモデルを使って、テキストを音声に合成できます。

Azure Al 音声経由で OpenAl テキスト読み上げの音声を使うこともできます。詳細については、Azure OpenAl Service または Azure Al 音
声経由の OpenAl テキスト読み上げ音声のガイドを参照してください。


# モデルの概要テーブルとリージョンの可用性 デプロイの種類別モデル

Azure OpenAl では、お客様はビジネスと使用のパターンに合ったホスティング構造を選択できます。このサービスで提供されるデプロ
イの2 つの主要な種類は、以下のとおりです。

● 標準にはグローバル デプロイ オプションが用意されており、トラフィックをグローバルにルーティングしてスループットを向上さ
せます。

· プロビジョニング済みはグローバル デプロイ オプションでも提供されており、お客様はプロビジョニングされたスループット ユニ
ットを購入して Azure グローバル インフラストラクチャ全体にデプロイできます。

実行される推論操作はどのデプロイもまったく同じですが、課金、スケール、パフォーマンスは大きく異なります。Azure OpenAl のデ
プロイの種類の詳細については、デプロイの種類に関するガイドを参照してください。

グローバル標準


# Global-Standard モデルの提供状況


<table>
<caption>〔〕 テーブルを展開する</caption>
<tr>
<th rowspan="2">リージョン</th>
<th rowspan="2">o3- mini.</th>
<th>01.</th>
<th rowspan="3">o1- preview. 2024-09-</th>
<th rowspan="2">o1- mini.</th>
<th rowspan="2">gpt- 40.</th>
<th>gpt-</th>
<th>gpt-</th>
<th>gpt-</th>
<th rowspan="3">gpt-4o- realtime- preview.</th>
<th rowspan="3">gpt-4o- realtime- preview.</th>
<th rowspan="3">gpt-4o- audio- preview.</th>
<th rowspan="3">gpt-4o- mini- realtime-</th>
<th rowspan="2">gpt-4o- mini-</th>
<th></th>
</tr>
<tr>
<th>2024-</th>
<th>4o、</th>
<th>4o、</th>
<th>4o-</th>
<th></th>
</tr>
<tr>
<th></th>
<th>2025-</th>
<th>12-17</th>
<th>2024-</th>
<th>2024</th>
<th>2024-</th>
<th>2024-</th>
<th>mini,</th>
<th>audio-</th>
<th></th>
</tr>
<tr>
<td></td>
<td>01-31</td>
<td rowspan="3"></td>
<td rowspan="3">12</td>
<td rowspan="3">09-12</td>
<td>年5</td>
<td>08-06</td>
<td>11-20</td>
<td>2024-</td>
<td>2024-12-</td>
<td>2024-10-</td>
<td rowspan="3">2024-12- 17</td>
<td rowspan="3">preview. 2024-12- 17</td>
<td>preview.</td>
<td></td>
</tr>
<tr>
<td rowspan="2"></td>
<td rowspan="2"></td>
<td rowspan="2">月 13 ⽇</td>
<td></td>
<td rowspan="2"></td>
<td rowspan="2">07-18</td>
<td rowspan="2">17</td>
<td rowspan="2">01</td>
<td rowspan="2">2024-12- 17</td>
<td rowspan="2"></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td>australiaeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>brazilsouth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
</table>


t

2

0

<!-- PageBreak -->

t
2
0


<table>
<tr>
<th rowspan="2">リージョン</th>
<th rowspan="3">o3- mini. 2025- 01-31</th>
<th rowspan="3">01. 2024- 12-17</th>
<th rowspan="3">o1- preview. 2024-09- 12</th>
<th rowspan="3">o1- mini, 2024- 09-12</th>
<th rowspan="2">gpt- 40. 2024 年5</th>
<th rowspan="2">gpt- 40% 2024- 08-06</th>
<th rowspan="2">gpt- 40. 2024- 11-20</th>
<th>gpt- 4o- mini,</th>
<th>gpt-4o- realtime- preview.</th>
<th rowspan="2">gpt-4o- realtime- preview. 2024-10-</th>
<th>gpt-4o- audio- preview.</th>
<th rowspan="3">gpt-4o- mini- realtime- preview. 2024-12- 17</th>
<th colspan="2" rowspan="2">gpt-4o- mini- audio- preview.</th>
</tr>
<tr>
<th>2024-</th>
<th>2024-12-</th>
<th>2024-12-</th>
</tr>
<tr>
<th></th>
<th>月 13 ⽇</th>
<th></th>
<th></th>
<th>07-18</th>
<th>17</th>
<th>01</th>
<th>17</th>
<th colspan="2">2024-12- 17</th>
</tr>
<tr>
<td>canadaeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>eastus</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>eastus2</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td></td>
</tr>
<tr>
<td>francecentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>germanywestcentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>japaneast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>koreacentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>northcentralus</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>norwayeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>polandcentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>southafricanorth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>southcentralus</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>southindia</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>spaincentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>swedencentral</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>☒ ✅</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>switzerlandnorth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>uaenorth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>uksouth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>westeurope</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>westus</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>☒ ✅</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>☒ ✅</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
<tr>
<td>westus3</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td></td>
</tr>
</table>


⊙ 注意

ほとんどの o シリーズモデルは、制限付きアクセスです。制限付きアクセス モデルの申請 のページから、アクセスを申請し
てください。 現在、o1-mini は、グローバル標準デプロイのすべてのお客様が利用できます。

一部のお客様には、o1-preview 制限付きアクセス リリースの一部として、o1-mini への標準(リージョン) デプロイ アクセスが
付与されています。現時点で、o1-mini 標準(リージョン) デプロイへのアクセスは拡大されていません。

この表には、微調整のリージョン別の提供状況は含まれていません。この情報については、微調整についてのセクションをご覧くださ
い。


# エンドポイント別の標準モデル

チャット入力候補

チャット入力候補

<!-- PageFooter="〔〕 テーブルを展開する" -->
<!-- PageBreak -->


<table>
<tr>
<th rowspan="3">リージョン</th>
<th>o1- preview.</th>
<th rowspan="5">o1- mini- 2024- 09-12</th>
<th rowspan="3">gpt- 40% 2024 年5</th>
<th>gpt- 40.</th>
<th rowspan="3">gpt- 4o- mini, 2024-</th>
<th rowspan="3">gpt- 4. 0613</th>
<th rowspan="3">gpt-4. 1106- Preview</th>
<th rowspan="5">gpt-4. 0125- Preview</th>
<th rowspan="3">gpt-4. vision- preview</th>
<th rowspan="3">gpt- 4. turbo- 2024-</th>
<th rowspan="3">gpt- 4- 32k. 0613</th>
<th rowspan="5">gpt-35- turbo, 0301</th>
<th rowspan="5">gpt-35- turbo. 0613</th>
<th rowspan="4">gpt-35- turbo. 1106</th>
<th rowspan="3">gpt-35 turbo. 0125</th>
</tr>
<tr>
<th>2024-09-</th>
<th rowspan="2">2024- 08-06</th>
</tr>
<tr>
<td>12</td>
</tr>
<tr>
<td></td>
<td></td>
<td rowspan="2">月 13 ⽇</td>
<td></td>
<td>07-18</td>
<td rowspan="2"></td>
<td></td>
<td rowspan="2"></td>
<td>04-09</td>
<td rowspan="2"></td>
<td rowspan="2"></td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>australiaeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>canadaeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>eastus</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>eastus2</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>francecentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
</tr>
<tr>
<td>japaneast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>northcentralus</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>norwayeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>southcentralus</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>southindia</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>swedencentral</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>☒ ✅</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
</tr>
<tr>
<td>switzerlandnorth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>uksouth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>westeurope</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>westus</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>☒ ✅</td>
</tr>
<tr>
<td>westus3</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</table>


## ( 注意

ほとんどの o シリーズモデルは、制限付きアクセスです。制限付きアクセス モデルの申請 のページから、アクセスを申請し
てください。 現在、o1-mini は、グローバル標準デプロイのすべてのお客様が利用できます。

一部のお客様には、o1-preview 制限付きアクセス リリースの一部として、o1-mini への標準(リージョン) デプロイ アクセスが
付与されています。現時点で、o1-mini 標準(リージョン) デプロイへのアクセスは拡大されていません。


## GPT-4 および GPT-4 Turbo モデルの可用性


### お客様のアクセスを選択する

Azure OpenAl のすべてのお客様が利用できる上記のリージョンに加え、一部の既存のお客様には、その他のリージョンでの GPT-4
のバージョンへのアクセスが許可されています。

〔〕 テーブルを展開する


<table>
<tr>
<td>モデル</td>
<td>リージョン</td>
</tr>
<tr>
<td rowspan="4">gpt-4 (0314) gpt-4-32k (0314)</td>
<td>米国東部</td>
</tr>
<tr>
<td>フランス中部</td>
</tr>
<tr>
<td>米国中南部</td>
</tr>
<tr>
<td>英国南部</td>
</tr>
<tr>
<td rowspan="4">gpt-4 (0613) gpt-4-32k (0613)</td>
<td>米国東部</td>
</tr>
<tr>
<td>米国東部 2</td>
</tr>
<tr>
<td>東日本</td>
</tr>
<tr>
<td>英国南部</td>
</tr>
</table>


<!-- PageFooter="GPT-3.5 モデル" -->
<!-- PageBreak -->

<!-- PageHeader="モデル バージョンを参照して、Azure OpenAl Service がモデル バージョンのアップグレードを処理する方法と、モデルを使用して GPT-3.5 Turbo デプロイのモデル バージョン設定を表示および構成する方法について説明します。" -->


# モデルの微調整


## ⊙ 注意

gpt-35-turbo - このモデルの微調整はリージョンのサブセットに限定され、基本モデルが使用可能なすべてのリージョンで使用でき
るわけではありません。

Azure OpenAl モデルを Azure Al Foundry プロジェクトで使用するか、プロジェクトの外部で使用するかによって、微調整をサポー
トするリージョンは異なります。


<table>
<caption>〔〕 テーブルを展開する</caption>
<tr>
<th>モデル ID</th>
<th>微調整リージョン</th>
<th>最大要求(トークン)</th>
<th>トレーニング データ(最大)</th>
</tr>
<tr>
<td rowspan="4">gpt-35-turbo (0613)</td>
<td>米国東部 2</td>
<td rowspan="2">4,096</td>
<td rowspan="4">2021 年9月</td>
</tr>
<tr>
<td>米国中北部</td>
</tr>
<tr>
<td>スウェーデン中部</td>
<td rowspan="2"></td>
</tr>
<tr>
<td>スイス西部</td>
</tr>
<tr>
<td rowspan="4">gpt-35-turbo (1106)</td>
<td>米国東部 2</td>
<td>入力:16,385</td>
<td rowspan="4">2021 年9月</td>
</tr>
<tr>
<td>米国中北部</td>
<td>出力:4,096</td>
</tr>
<tr>
<td>スウェーデン中部</td>
<td rowspan="2"></td>
</tr>
<tr>
<td>スイス西部</td>
</tr>
<tr>
<td rowspan="3">gpt-35-turbo (0125)</td>
<td>米国東部 2 米国中北部</td>
<td rowspan="3">16,385</td>
<td rowspan="3">2021 年9月</td>
</tr>
<tr>
<td>スウェーデン中部</td>
</tr>
<tr>
<td>スイス西部</td>
</tr>
<tr>
<td>gpt-4 (0613) 1</td>
<td>米国中北部 スウェーデン中部</td>
<td>8192</td>
<td>2021 年9月</td>
</tr>
<tr>
<td>gpt-4o-mini (2024-07-18)</td>
<td>米国中北部 スウェーデン中部</td>
<td>入力:128,000 出力:16,384 トレーニング例のコンテキスト長: 64,536</td>
<td>2023年10月</td>
</tr>
<tr>
<td rowspan="3">gpt-4o (2024-08-06)</td>
<td>米国東部 2</td>
<td>入力:128,000</td>
<td rowspan="3">2023年10月</td>
</tr>
<tr>
<td>米国中北部</td>
<td rowspan="2">出力:16,384 トレーニング例のコンテキスト長: 64,536</td>
</tr>
<tr>
<td>スウェーデン中部</td>
</tr>
</table>

1 GPT-4 は現在パブリック プレビューの段階です。


## アシスタント(プレビュー)

アシスタントの場合は、サポートされているモデルとサポートされているリージョンの組み合わせが必要です。特定のツールと機能には
最新モデルが必要です。次のモデルは、Assistants API、SDK、Azure Al Foundry で使用できます。次の表は、従量課金制に関するもので
す。 プロビジョニング済みスループット ユニット(PTU) の可用性については、プロビジョニング済みスループットに関する記事を参照し
てください。一覧で示されているモデルとリージョンは、Assistants v1 と v2 の両方で使用できます。以下に示すリージョンでサポート
されている場合に、グローバル標準モデルを使用できます。


<table>
<caption>〔〕 テーブルを展開する</caption>
<tr>
<th>リージョン</th>
<th>gpt- 4o、 2024 年 5 月 13 ⽇</th>
<th>gpt- 4o、 2024- 08-06</th>
<th>gpt-4o- mini- 2024-07- 18</th>
<th>gpt- 4. 0613</th>
<th>gpt-4. 1106- Preview</th>
<th>gpt-4. 0125- Preview</th>
<th>gpt-4. turbo- 2024-04- 09</th>
<th>gpt-4- 32k. 0613</th>
<th>gpt-35- turbo- 0613</th>
<th>gpt-35- turbo- 1106</th>
<th>gpt-35- turbo- 0125</th>
<th>gpt-35- turbo- 16k, 0613</th>
</tr>
<tr>
<td>australiaeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>-</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>✅ ☒</td>
<td>☒ ✅</td>
</tr>
<tr>
<td>eastus</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>-</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
</tr>
<tr>
<td>eastus2</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>-</td>
<td>☒ ✅</td>
<td>☒ ✅</td>
</tr>
</table>


<!-- PageBreak -->


<table>
<tr>
<th>リージョン</th>
<th>gpt- 40. 2024 年 5 月 13 ⽇</th>
<th>gpt- 40% 2024- 08-06</th>
<th>gpt-4o- mini- 2024-07- 18</th>
<th>gpt- 4. 0613</th>
<th>gpt-4. 1106- Preview</th>
<th>gpt-4. 0125- Preview</th>
<th>gpt-4. turbo- 2024-04- 09</th>
<th>gpt-4- 32k, 0613</th>
<th>gpt-35- turbo- 0613</th>
<th>gpt-35- turbo, 1106</th>
<th>gpt-35- turbo, 0125</th>
<th>gpt-35- turbo- 16k, 0613</th>
</tr>
<tr>
<td>francecentral</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>japaneast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>norwayeast</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>southindia</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
</tr>
<tr>
<td>swedencentral</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>uksouth</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
</tr>
<tr>
<td>westus</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
</tr>
<tr>
<td>westus3</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>✅ ☒</td>
<td>-</td>
</tr>
</table>


## モデルの廃止

モデルの廃止に関する最新情報については、モデル廃止ガイドに関する記事をご覧ください。


## 次のステップ

· モデルの廃止と非推奨

● Azure OpenAl モデルの操作に関する詳細を確認する

● Azure OpenAl の詳細についてご覧ください

● Azure OpenAl モデルの微調整に関する詳細を確認する


## フィードバック

このページはお役に立ちましたか?

Yes

「いいえ

製品フィードバックの提供

Microsoft Q&A でヘルプを表示する
