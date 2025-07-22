# NextApp+tailwind開発用！

## git url 変えるんやで！

```Bash
git remote set-url origin https://github.com/〇〇
```

```Bash
git remote set-url --push origin https://github.com/〇〇
```

# Readme テンプレート
<div id="top"></div>

## 使用技術一覧
<p style="display: inline">
<img src="https://img.shields.io/badge/-Node.js-000000.svg?logo=node.js&style=for-the-badge">
<img src="https://img.shields.io/badge/-Next.js-000000.svg?logo=next.js&style=for-the-badge">
<img src="https://img.shields.io/badge/-TailwindCSS-000000.svg?logo=tailwindcss&style=for-the-badge">
<img src="https://img.shields.io/badge/-React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
</p>

## 目次

1. [プロジェクトについて](#プロジェクトについて)
2. [環境](#環境)
3. [ディレクトリ構成](#ディレクトリ構成)
4. [開発環境構築](#開発環境構築)
5. [トラブルシューティング](#トラブルシューティング)

## プロジェクトについて

一般社団法人TSUNAGUのwebサイト

## 環境

<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

| 言語・フレームワーク  | バージョン |
| --------------------- | ---------- |
| Node.js               | 16.17.0    |
| React                 | 18.2.0     |
| Next.js               | 13.4.6     |

## ディレクトリ構成
```
├── app/
│   ├── api/
│   │   └── hello/
│   │       └── route.ts ←/api/helloのAPIを実装
│   ├── actions/
│   │   ├── aaa-action.ts ←サーバーアクションを実装
│   │   └── hello-action.ts ←APIを作らずにここで実装することも可能
│   ├── page1/
│   │   ├── [id]/
│   │   │   ├── page.module.css ←個別のCSSの実装
│   │   │   ├── actions.css ←個別でサーバーアクションの実装も可能
│   │   │   └── page.tsx ←/page1/1とかのページを実装
│   │   ├── page.module.css
│   │   └── page.tsx ←/page1のページを実装
│   ├── page.tsx ←/のページを実装
│   ├── loading.tsx ←ロード中ページを実装
│   ├── layout.tsx ←全体レイアウトを実装
│   └── globals.css ←全体のcssを実装
```
