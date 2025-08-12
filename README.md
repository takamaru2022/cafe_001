# Cafe VibeCording Website

モダンで洗練されたカフェ「Cafe VibeCording」のウェブサイトです。

## 概要

東京駅から徒歩1分の好立地にあるブルックリン風カフェのコーポレートサイトです。
こだわりの焙煎コーヒーと厳選素材を使用したメニューを提供しています。

## 特徴

- **モバイルファーストデザイン**: スマートフォン優先のレスポンシブ対応
- **アクセシビリティ**: Google Material Iconsを使用した直感的なUI
- **静的サイト**: データベースを使用しない軽量なHTML/CSS/JavaScript構成
- **SEO対応**: 適切なメタタグとセマンティックHTML

## 技術仕様

### フロントエンド
- **HTML5**: セマンティックマークアップ
- **CSS3**: CSS Grid, Flexbox, カスタムプロパティ使用
- **JavaScript**: モバイルメニュー、スムーススクロール対応
- **フォント**: Noto Sans JP, Playfair Display, Material Icons

### カラーパレット
- **Primary**: #4B2E2A (Deep Brown)
- **Secondary**: #F8F5E7 (Ivory)
- **Accent**: #8B6F47

## ページ構成

1. **Home** (`index.html`) - ヒーロー画像、魅力紹介
2. **イベント案内** (`events.html`) - 今後・過去のイベント情報
3. **当店の特色** (`about.html`) - 焙煎方針、食材調達、空間コンセプト
4. **人気メニュー** (`menu.html`) - おすすめドリンク・フード
5. **所在地** (`location.html`) - アクセス情報、Google Maps

## ローカル環境での実行

```bash
# HTTPサーバーを起動（Python 3の場合）
python3 -m http.server 8000

# ブラウザでアクセス
http://localhost:8000
```

## プロジェクト構成

```
cafe_001/
├── index.html          # ホームページ
├── events.html         # イベント案内
├── about.html          # 当店の特色
├── menu.html           # 人気メニュー
├── location.html       # 所在地
├── styles.css          # メインスタイル
├── events.css          # イベントページスタイル
├── about.css           # 特色ページスタイル
├── menu.css            # メニューページスタイル
├── location.css        # 所在地ページスタイル
├── script.js           # JavaScript機能
├── images/             # 画像フォルダ
│   ├── cafe_vibecoding top.png
│   ├── cafe_brend.png
│   ├── cafe_toast.png
│   ├── cafe_roast.png
│   ├── cafe_interior.png
│   ├── cafe_vegetable.png
│   ├── coffee_roastworkshop.png
│   ├── coffee_live_.png
│   ├── icon_Instagram.png
│   └── icon_X.png
├── image-guide.html    # 画像使用ガイド
└── README.md          # プロジェクト説明

```

## 店舗情報

- **店舗名**: Cafe VibeCording
- **住所**: 〒123-4567 東京都千代田区桜満開1-1-1
- **営業時間**: 月〜金 13:00〜17:00
- **定休日**: 土・日・祝日
- **アクセス**: JR東京駅 丸の内中央口より徒歩1分

## 開発者

Created with [Claude Code](https://claude.ai/code)

## ライセンス

© 2025 Cafe VibeCording. All rights reserved.