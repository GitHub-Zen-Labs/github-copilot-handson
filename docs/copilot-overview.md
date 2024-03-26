# GitHub Copilot のキャッチアップ

ここでは GitHub Copilot と、新たに 2024年に登場した GitHub Copilot Enterprise の情報をキャッチアップします。  

> [!NOTE]
> 既に理解している方は、[ここをクリック](./README.md) してセルフペースドハンズオンを開始しましょう。

## GitHub Copilot とは

### 概要

GitHub Copilotは、GitHubが開発した開発に特化したAIアシスタントです。コード補完や生成、解説を行うことができます。始めはコード補完のみでしたが、今ではチャットやCLI上など、さまざまなシーンでAIの支援を活用できるようになってきています。

GitHub Copilot の代表的な機能を3つ紹介します。

機能 | 説明
---- | ----
**GitHub Copilot(Code completion)** | AIによるコード補完。IDEの拡張機能として提供される。LLMモデルはGPT-3.5 Turbo（※1）。
**GitHub Copilot Chat** | IDEまたはモバイルアプリ（※2）上で、会話形式でAIによるコード生成、解説を支援する。LLMモデルはGPT-4（※3）。
**Copilot in the CLI** | AIによるコマンドの生成支援

> - ※1 2023年6月時点の情報。
>   - 参考: [GitHub Copilot - June 29th Update - The GitHub Blog](https://github.blog/changelog/2023-06-29-copilot-june-2023-update/#code-completion-improvements)  
>   GitHub Copilot is now even more powerful and responsive for developers, thanks to a new model powered by GPT-3.5 Turbo through the collaboration across OpenAI, Azure AI, and GitHub that offers 13% latency improvements.
> - ※2 GitHubのモバイルアプリで提供される予定。
> - ※3 GitHub Universe 2023 (2023年11月) 時点の情報。
>   - 参考: [Universe 2023: Copilot transforms GitHub into the AI-powered developer platform - The GitHub Blog](https://github.blog/2023-11-08-universe-2023-copilot-transforms-github-into-the-ai-powered-developer-platform/)

### 料金プランと機能

プラン | 概要
----|----
**GitHub Copilot Individual** | 個人利用向けプラン。データの収集の可否を選択できる。
**GitHub Copilot Business** | Organization単位、Enterprise単位での利用。Individualと異なり、データの収集は一律行わない。
**GitHub Copilot Enterprise** | Individual/Business の機能に加え、多くの機能を提供。詳細は後述。

#### GitHub Copilot Enterprise について

GitHub Copilot Enterpriseは、GitHub Universe 2023で発表され、2024年2月に GA しました。GitHub Copilot Businessの機能に加え、GitHub を AI プラットフォームとして進化するための多くの機能が追加されます。その一部は以下です。

- **GitHub Copilot Chat in GitHub.com**: GitHub.com 上でリポジトリの内容をコンテキストに含めて、コードの生成や解説が実現できます。
- **GitHub Copilot pull request summaries**: プルリクエスト作成時に、プルリクエストで行われた変更の概要、どのファイルに影響があるか、レビュアーがレビューを行う際に何に注目すべきかの文章を作成できます。

GitHub Enterprise ではこのほかにも多くの機能が提供されています。提供されているすべての機能や料金プランごとの具体的な機能の差分は、以下のリンクから確認可能です。

- [Pricing - GitHub Copilot · Your AI pair programmer](https://github.com/features/copilot#pricing)

<br>

## ハンズオンの開始

概要の説明はここまでです。
ここからは、以下よりセルフペースドハンズオンを開始しましょう。

- [セルフペースドハンズオンの開始](./README.md)
