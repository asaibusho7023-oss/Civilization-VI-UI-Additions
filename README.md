# Civilization VI - Terrace Farm Mod Ver3

## 概要
Civilization VIの棚畑（Terrace Farm）の性能をバフするModBuddyプロジェクトです。

**Ver3の性能:**
- 食料: +100
- 生産力: +200
- 住宅: +30

## 導入方法

### ModBuddyで編集する場合
1. ModBuddyを起動
2. `File` → `Open` → `TerraceFarm_Ver3.civ6proj` を選択
3. 編集後、`Build` をクリック
4. ビルド完了後、ゲームで有効化

### ゲームに直接インストールする場合
1. このフォルダ全体を以下にコピー:
   ```
   C:\Users\[ユーザー名]\Documents\My Games\Sid Meier's Civilization VI\Mods\
   ```
   (Windows の場合)

2. Civ6を起動し、Modsタブから「Terrace Farm Ver3」を有効化

## ファイル構成
```
TerraceFarm_Ver3/
├─ TerraceFarm_Ver3.civ6proj       ModBuddyプロジェクトファイル
├─ TerraceFarm_Ver3.modinfo        MOD定義ファイル
└─ Gameplay/
   └─ Data/
      └─ TerraceFarm_Ver3.xml      ゲームデータ
```

## 友達と共同編集する場合
1. このリポジトリをクローン: `git clone https://github.com/asaibusho7023-oss/Civilization-VI-UI-Additions.git`
2. `TerraceFarm_Ver3` フォルダをModBuddyで開く
3. 編集後、push してシェア

## 注意事項
- このModは棚畑の数値を上書きします
- 他のMODとの競合がないか確認してください
- バージョンアップ時は `.modinfo` の version を更新してください

## ライセンス
MITライセンス

## 作成者
asaibusho7023-oss
