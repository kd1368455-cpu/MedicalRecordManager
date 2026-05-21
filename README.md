# MedicalRecordManager
Java（Eclipse）で作成した医療データ管理システムです。  
患者情報の登録、一覧表示、診療記録の追加、CSV保存など、  
業務システムの基本機能（CRUD）を実装しています。

---

## ■ 使用技術
- Java 17
- Eclipse
- CSV 出力（FileWriter / BufferedWriter）

---

## ■ 主な機能
### ● 患者登録
- 名前、年齢、性別を入力して登録できます。

### ● 患者一覧表示
- 登録済みの患者を一覧で表示します。

### ● 診療記録の追加
- 患者ごとに診療内容を追加できます。

### ● CSV 保存
- medical_records.csv に患者情報と診療記録を出力します。

---

## ■ プロジェクト構成
MedicalRecordManager/  
├─ src/  
│  ├─ MedicalRecordManager.java   // メイン処理（メニュー・操作）  
│  ├─ Patient.java                // 患者データクラス  
│  └─ (必要なら追加クラスをここに配置)  
├─ medical_records.csv            // CSV出力ファイル（実行後に生成）  
└─ README.md                      // GitHub説明文  

---

## ■ 実行方法
1. Eclipse にプロジェクトをインポート  
2. `MedicalRecordManager.java` を実行  
3. コンソールメニューから操作できます  

---

## ■ 目的
医療・公共・業務システムなど、**業務系アプリケーションで求められる基本機能（CRUD・検索・データ保存）**を備えたデータ管理システムを制作しました。

実務で頻繁に利用される「データ管理」「検索」「CSV出力」を実装し、  
**業務ロジックの理解と基礎的なアプリケーション開発能力を示すこと**を目的としています。
