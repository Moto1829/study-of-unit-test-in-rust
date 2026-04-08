# study-of-unit-test-in-rust

Rust言語における単体テストを、基礎から実践まで体系的に学ぶための学習コンテンツです。

単体テストの書き方や実行方法だけでなく、スタブやモックを用いた依存の切り分け、単体テストで頻出する処理の扱い方、標準外crateを活用したテスト手法まで、実務で必要になりやすい論点を広く扱います。

また、Rustの型システムが単体テストに対してどのようなメリットをもたらすのかも重要なテーマとして扱います。所有権、借用、trait、enum、Result、OptionといったRust特有の仕組みが、バグの混入を防ぎつつテストしやすい設計をどう支えるのかを整理して解説します。

## 目次

1. [はじめに](contents/01-introduction.md)
2. [単体テストの作り方](contents/02-writing-unit-tests.md)
3. [単体テストの実行方法](contents/03-running-tests.md)
4. [スタブやモックを使ったテスト](contents/04-stubs-and-mocks.md)
5. [単体テストでよくやる処理](contents/05-common-testing-patterns.md)
6. [標準外crateを使ったテスト](contents/06-testing-with-external-crates.md)
7. [Rustの型システムと単体テスト](contents/07-rust-type-system-and-testing.md)
8. [到達目標と今後の拡張](contents/08-goals-and-roadmap.md)

## このプロジェクトで学べること

- Rustにおける単体テストの基本構文
- `#[cfg(test)]` と `#[test]` の役割
- `cargo test` を使ったテストの実行方法
- 正常系と異常系のテスト設計
- スタブやモックを使った依存の分離
- 単体テストでよく扱うデータ準備や状態検証の考え方
- 標準外crateを用いたアサーション強化やモック化
- Rustの型システムがテスト容易性に与える影響

詳細は上記の章ファイルを順に読めば追える構成にしてあります。READMEは全体像の把握と導線のための索引として使ってください。
