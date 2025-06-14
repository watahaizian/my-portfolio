# My Personal Portfolio

これは、自身のスキルと制作物を紹介するために構築した、個人のポートフォリオサイトです。

**✨ Live Demo: [https://watahaizian.com](https://watahaizian.com)**

---

## 概要 (Overview)

このWebサイトは、私のこれまでの学習成果と開発したプロジェクトをまとめた、個人のポートフォリオです。高速な静的サイト生成と優れた開発体験を両立する `Astro` フレームワークをメインに、モダンな技術を用いて構築しました。

デザインは `Tailwind CSS` を用いて、クリーンで分かりやすいUIを目指しました。

## 使用技術 (Technology Stack)

このポートフォリオサイトの構築に使用した主な技術です。

-   **フレームワーク**: `Astro`
-   **言語**: `TypeScript`
-   **スタイリング**: `Tailwind CSS`
-   **パッケージマネージャー**: `pnpm`
-   **ホスティング**: `Cloudflare Pages`

## ローカル環境での実行 (Getting Started)

1.  **リポジトリをクローン**
    ```bash
    git clone https://github.com/watahaizian/my-portfolio.git
    cd my-portfolio
    ```

2.  **依存パッケージをインストール**
    ```bash
    pnpm install
    ```

3.  **開発サーバーを起動**
    ```bash
    pnpm dev
    ```
    ブラウザで `http://localhost:4321` を開いてください。

## デプロイ (Deployment)

このサイトはCloudflare Pagesにデプロイされており、GitHubの`main`ブランチにプッシュされるたびに、自動的にビルドとデプロイが実行されます。

-   **ビルドコマンド**: `pnpm build`
-   **出力ディレクトリ**: `dist`

## ライセンス (License)

This project is licensed under the MIT License.