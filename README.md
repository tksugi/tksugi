<h1 align="center">tksugi</h1>

<p align="center">
  <strong>Backend Development · Web Applications · Automation</strong><br>
  日常の小さな不便を、使いやすい仕組みに変える。
</p>

<p align="center">
  <a href="https://github.com/tksugi/rakushifu-viewer#技術構成"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"></a>
  <a href="https://github.com/tksugi/rakushifu-viewer#技術構成"><img src="https://img.shields.io/badge/Flask-181717?style=flat-square&amp;logo=flask&amp;logoColor=white" alt="Flask"></a>
  <a href="https://github.com/tksugi/rakushifu-viewer#cloudflare-workersで実行する"><img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&amp;logo=cloudflare&amp;logoColor=white" alt="Cloudflare"></a>
</p>

<p align="center">
  <a href="#about">自己紹介</a> &nbsp; / &nbsp;
  <a href="#featured-project">制作物</a> &nbsp; / &nbsp;
  <a href="#tech-stack">使用技術</a> &nbsp; / &nbsp;
  <a href="https://github.com/tksugi?tab=repositories">公開リポジトリ</a>
</p>

---

## About

バックエンド開発と業務自動化を中心に、WebアプリやLINEを使ったサービスを作っています。
シフトの確認や学食メニューの更新など、身近な作業を少し便利にすることに関心があります。

## Featured Project

### [rakushifu-viewer](https://github.com/tksugi/rakushifu-viewer)

**シフトの確認と、予定シフトからの給与概算をひとつの画面で。**

すかいらーくグループ向けの「らくしふ」のシフト・メンバー情報を閲覧する非公式Webアプリです。
月間カレンダー、日別の勤務メンバー、名前検索、給与概算に対応しています。

<p align="center">
  <a href="https://github.com/tksugi/rakushifu-viewer#画面例">
    <img src="https://raw.githubusercontent.com/tksugi/rakushifu-viewer/main/docs/images/calendar-desktop.png" alt="rakushifu-viewerの月間カレンダー。架空のスタッフとシフトを使ったPC画面" width="760">
  </a>
  <br>
  <sub>架空データを使った画面例。PC・スマートフォンに対応。</sub>
</p>

Python / Flaskを使ったローカル版と、Cloudflare Workers版を用意しています。
ログインなしで架空データのサンプルを試せます。

[ソースコード・起動手順](https://github.com/tksugi/rakushifu-viewer#クイックスタート) · [画面例](https://github.com/tksugi/rakushifu-viewer#画面例) · [技術仕様](https://github.com/tksugi/rakushifu-viewer/blob/main/docs/architecture.md)

### CIT 学食メニュー in LINE

**学食のメニューと混雑状況を、LINEから確認。**

千葉工業大学の3つの食堂を対象に、メニューとライブカメラ画像を案内する非公式サービスです。

- メニューのPDFを画像に変換し、LINEのトーク画面に表示
- スケジュール実行と変更検知で、メニューの更新を自動化
- Cloudflare Workers / KVを使ったサーバーレス構成

## Tech Stack

| 分野 | 使用技術 |
| --- | --- |
| バックエンド | Python · Flask · FastAPI |
| Web画面 | HTML · CSS · JavaScript |
| クラウド・データ | Cloudflare Workers · KV · Durable Objects · MySQL |
| 外部サービス連携 | LINE Messaging API |
| 開発環境 | Linux · Git · GitHub Actions |

---

<p align="center">
  <a href="https://github.com/tksugi?tab=repositories">公開リポジトリを見る →</a>
</p>
