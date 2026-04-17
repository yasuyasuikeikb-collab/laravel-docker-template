# laravel-docker-template

# Laravel + Docker 開発環境テンプレート

## 概要
Laravel の開発環境を Docker で構築するためのテンプレートです。  
Laravel 本体は `src` ディレクトリ内に含まれています。

### 構成
- nginx
- php (Laravel)
- MySQL
- phpMyAdmin

---

## セットアップ手順

### 1. ルート直下に `.env` を作成
Docker Compose で使う UID / GID を設定します。

```bash
cp .env.example .env