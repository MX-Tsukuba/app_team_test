# app_team_test

アプリケーション班のテスト用リポジトリ

## 環境構築

```batch
環境構築をする際のコマンドを書く
```

## ローカルサーバーの起動

```batch
ローカルサーバーを起動する際のコマンドを書く
```

## ビルド

```batch
ビルドする際のコマンドを書く
```

## 使用するパッケージマネージャー

### npm

## 使用を推奨している Visual Studio Code の拡張機能

### Prettier - Code formatter

## 開発時のルール

1. 作業しようとする際には、まずその内容の issue を作成する

    ※ issue を作成した際、必ず Label も付ける

2. レポジトリを clone し、正しいと思われるブランチ名で develop ブランチから feature ブランチを作成する

    ※ 取り組もうとしている issue にセルフで Assign する

3. 作業終了後、develop ブランチに PRs をし、各自コンフリクトを解消してからマージする

## branch のルール

#### 実際に完成品を置いておくブランチ

※main ブランチは、develop ブランチ以外のマージを許可しない

-   main

#### 開発をしている際の PRs をするブランチ (Default branch)

※基本的に、feature ブランチの PRs 先は develop ブランチ

-   develop

### 以下のブランチは、すべて develop ブランチにマージすること

#### 機能を追加する際に作成するブランチ

-   feature/feat/#[issue-number]-[issue-summary]

    example) feature/feat/#12-add-card-button-component

#### バグ修正をする際に作成するブランチ

-   feature/bugfix/#[issue-number]-[issue-summary]

    example) feature/bugfix/#12-fix-button-function

#### バグ以外の修正や変更をする際に作成するブランチ

-   feature/fix/#[issue-number]-[issue-summary]

    example) feature/fix/#12-change-title

#### 設定の変更等をする際に作成するブランチ

-   feature/config/#[issue-number]-[issue-summary]

    example) feature/config/#12-add-prettier-config

#### その他、以下の条件の下で勝手に新たな種類の feture ブランチを作成してもよい

-   feature/[github の username]/[自由にして良い部分]/#[issue-number]-[issue-summary]

    example) feature/myxogastria0808/nyoki/#112-add-my-config-file
