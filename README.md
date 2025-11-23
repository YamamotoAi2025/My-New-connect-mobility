# My-New-Connept-Mobility: Off-Grid Senior Car with Peltier AC & Air-Gapped AI

## コンセプト（Concept）
老人用シニアカーを「完全オフグリッドの移動AI基地」に改造。ペルチェ素子で夏45℃を25℃に、ソーラー＋LiFePO4で無給電走行。ネット接続ゼロ、エアギャップ100%でプライバシー死守。

## 購入済みパーツ（Purchased Parts）
| パーツ | スペック | 役割 |
|--------|----------|------|
| シニアカー本体 | 4輪電動カート | ベース車両 |
| ペルチェ素子 | TEC1-12710 ×8 | 空調冷却（120W/枚） |
| LiFePO4バッテリー | 12V 100Ah ×2 | 永久電源 |
| ソーラーパネル | 100W ×2 | 太陽光充電 |
| ナノPC | RK3588 | オフラインAIコア |

## 次ステップ
1. ペルチェ実装テスト（温度データアップ）
2. 配線図追加（手書きOK）
3. AI統合: Ollamaで車内分散処理

[スケッチ画像リンク] 


# My-New-connept-mobility
The structures of My New concept mobility

---

KKK06 Mobility – Concept Design

Overview

KKK06 Mobility は、次世代モビリティを目指した小型移動体のコンセプトモデルです。
都市部や研究フィールドにおいて、柔軟かつ安全に移動できることを目的に設計されています。

形式: コンパクト2WDかつ５輪車両

用途: パーソナルモビリティ／研究用プラットフォーム
実践使用による改良プロセスが大切

速度域: 4 km/h 〜 8 km/h（歩行に近い速度帯で安全性を重視）

操縦方式: ジョイスティック／操縦桿コントロール

2WDの5輪モビリティ

コクピットは
ディスプレイ
キーボード
マウス
操縦桿
のシンプル設計→初期のレイアウト

太陽光パネルにてリチウム鉄バッテリーを充電
LLM搭載
自動運転
超音波センサーによる衝突防止
シニアカーの範疇

## 外観イメージ（手描きスケッチ）

<p align="center">
  <img src="https://github.com/YamamotoAi2025/My-New-connect-mobility/blob/main/IMG_20250919_060726.jpg" alt="KKK06 Sketch 1" width="48%">
  <img src="https://github.com/YamamotoAi2025/My-New-connect-mobility/blob/main/IMG_20250919_060731.jpg" alt="KKK06 Sketch 2" width="48%">
</p>
Features

モジュール式設計
外装パネルを簡単に組み替え可能。実験用途や展示用途に対応。

高い安定性
複数車輪による低重心設計。狭いスペースや不整地でも安定走行。

拡張可能なインターフェイス
カメラ、センサー、スタンドアロンAI（例：愛ちゃんAI）を搭載可能。
移動アシスタントや作業支援用プラットフォームとしての活用を想定。

安全性
移動速度を制限し、衝突や転倒のリスクを最小化。


Sketches

上の写真参照

正面図: 多角形ながら丸いイメージ

上面図: 全面アクリル貼りのトランスピアレント構造にネモ船長のノーチラス号の古風な錆びたイメージを両立させる

側面図: 車輪配置と低重心フレーム構造


Notes

本モデルは研究・展示目的の試作ですが、僕の私的利用に活用してデータを取る予定です。開発は実際の利用による改良プロセスが大切です。




---

操縦面（コクピットレイアウト）

前面ディスプレイ

中央に大画面ディスプレイを配置

移動情報（速度・方向）、センサー映像、AIアシスタントUIを表示

将来的にカメラや外部センサーからのリアルタイム情報を統合表示


入力デバイス

キーボード: 前面下部に配置、PC的な操作やAIへの指令入力に使用

マウス: キーボード横に設置、GUI操作や細かい制御に対応

操縦桿（ジョイスティック）: 右側に配置し、移動操作のメインインターフェイスとする

前後：前進／後退

左右：旋回

追加ボタン：速度モード切替、緊急停止



補助インターフェイス

音声入力（マイク）＋AI応答（スピーカー）

将来的にヘッドマウントディスプレイ（HMD）やタッチパネルとの併用も考察


---


## Cockpit Layout

- **Main Display**: Front-mounted, showing navigation, sensor data, and AI assistant interface.
- **Keyboard**: Positioned at the lower front, for text input and AI commands.
- **Mouse**: Located beside the keyboard for GUI operations.
- **Joystick (Right-hand side)**: Primary driving control.
  - Forward/Backward: Move vehicle
  - Left/Right: Steering
  - Additional buttons: Mode switch, emergency stop
- **Voice I/O**: Microphone + speaker for AI interaction

ｰｰｰ

