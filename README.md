**個人開発作品**
# 「Dice Re:make -ダイスリメイク-」
**制作・立案**　佐藤 侑牙（サトウ ユウガ）

## [前作はこちらから ←](https://github.com/yuuga25/DiceQuest)
こちらをご覧いただいた後に、読んでいただくとより、本作品について理解できると思われます。


- [概要](https://github.com/yuuga25/DiceQuest_new/edit/main/README.md#%E6%A6%82%E8%A6%81)
- [使用技術]()
- [ゲーム内容]()
    - [プレイ画面]()
    - [プレイ動画]()
- [気を付けた・こだわった部分]()
- [感想]()

## 概要

私が通っている、バンタンゲームアカデミー高等部では年に数回**審査会**があり、二年次の2回目（2022年 2月末）の審査会に向けて作成した作品です。    
結果は、最優秀賞を頂けました。

開発期間：2022年 1月～2月

###### ※審査会：普段授業を行っていただいているプロの講師の方に、個人で開発した作品を評価していただく会

### コンセプト
去年2月の審査会で制作したゲームのリメイク  
複数人で遊べるソーシャルゲームを作る

### ターゲット・プラットフォーム
10代後半～20代後半 / スマートフォン（Android・iOS）

## 使用技術
**Unity**  
**PlayFab**  
**~~Photon~~**  

## ゲーム内容
### [~~解説動画~~ ←制作中です]()
基本的には前作のゲームシステムを採用し、拡張性の無かった強化システムを撤廃して、  
新たにキャラクターを取り入れることで、よりソーシャルゲームに近いものを目指しました。  
残念ながら、制作期間の都合上マルチプレイは実装できませんでしたが、今後のブラッシュアップで追加する予定です。
## アウトゲーム
### ・タイトル画面 / ホーム画面
![Title](https://user-images.githubusercontent.com/79131217/184515887-efb53789-a90a-4edb-be1d-6c0285eba26d.PNG)
![Home](https://user-images.githubusercontent.com/79131217/184515870-f51f72f9-00c6-4761-bc94-2df4a58e6402.PNG)  

***
### ・キャラクター画面
キャラクター要素を取り入れたことで、新たに追加された「**編成・キャラクター強化・売却・図鑑 etc.**」
![Character](https://user-images.githubusercontent.com/79131217/184515853-ceb5416a-9775-4e48-95d5-bde400cd1888.PNG)

***
### ・編成  
所持しているキャラクターから挑戦するステージに合ったキャラクターを4体選んで編成を組みます  
![Organization](https://user-images.githubusercontent.com/79131217/184515875-ce6bc05b-b7dc-4c81-8652-a38d6793de8a.PNG)

***
### ・強化
強化したキャラクターを選んで、最大15体を所持しているキャラクターから選んで所持金と共に消費することで選択キャラクターを強化できます  
![strengthen](https://user-images.githubusercontent.com/79131217/184515885-23163fab-4d62-4543-9ac9-8729375c153e.PNG)
![strengthen_1](https://user-images.githubusercontent.com/79131217/184515886-02d9e69b-30ef-4499-8377-eb63c91b302f.PNG)

***
### ・売却
所持数が最大になってしまった時に、所持しているキャラクターを売却することで所持金に変換することができます  
![sale](https://user-images.githubusercontent.com/79131217/184515879-5355dcfe-0470-4a28-9f1c-3c1c8690d6e1.PNG)

***
### ・キャラクター一覧
所持しているキャラクターを一覧で表示することができ、キャラクターのステータスを見ることができます  
また条件を指定してソートすることも可能です（他 編成・強化・売却・図鑑などでも可能）  
![list](https://user-images.githubusercontent.com/79131217/184515873-714422dd-264e-40e4-a452-c23d32372755.PNG)

***
### ・キャラクターステータス / コーデチェンジ
キャラクター一覧画面から遷移し、キャラクターの細かいステータスを確認することができます  
キャラクターによってはコーデチェンジを行うことも可能です(コーデによる性能の差はありません)  
![Status](https://user-images.githubusercontent.com/79131217/184515884-d86749b4-d861-4461-9d65-2ed8589ffe41.PNG)
![outfitChange](https://user-images.githubusercontent.com/79131217/184515877-a771b317-f7a0-496b-94dc-be4aa189e1f8.PNG)

***
### ・図鑑
ゲームで存在しているキャラクターたちを一覧で見ることができます(全44種 +α)  
既に一度獲得しているキャラクターはロックが外れ、未所持キャラクターはロックがかかっています  
![pictorial book](https://user-images.githubusercontent.com/79131217/184515878-2a96fcfc-7dfe-4640-94f7-0cb978caff1b.PNG)

***
### ・ガチャ
魔法石を消費することで、キャラクターを新規入手することができます  
日替わりでピックアップのキャラクターが切り替わります  
![Gacha](https://user-images.githubusercontent.com/79131217/184515866-cee5bdb5-a125-4780-8b63-88b52197bdee.PNG)
![Gacha_Result](https://user-images.githubusercontent.com/79131217/184515867-66d0f57f-9510-423c-bb7f-7cea8af6788a.PNG)

***
### ・ショップ
ガチャでは入手できないキャラクターや、特別なコーデ、魔法石(ハリボテ)を購入することができます  
![Shop_Character](https://user-images.githubusercontent.com/79131217/184515880-89216190-2fac-439c-8445-0ddefbab70c7.PNG)
![Shop_Costume](https://user-images.githubusercontent.com/79131217/184515881-5300146c-aa9c-483c-bc01-93e340421bef.PNG)
![Shop_magicStone](https://user-images.githubusercontent.com/79131217/184515882-20ce10d2-d4e1-45dc-a83c-7c800c8abd21.PNG)

***
### ・オプション
プレイヤーネームとゲーム内ボリュームの変更が可能です  
![Option](https://user-images.githubusercontent.com/79131217/184515874-c5d1f7e6-a261-4c96-b369-0203dd067e31.PNG)

***
### ・ステージ選択
推奨レベル5 ~ 100から好きなステージを選択して挑戦することができます  
![StageSelect](https://user-images.githubusercontent.com/79131217/184515883-b1eed349-1200-4aed-8409-e1cee6dfc0b5.PNG)
![confirmationScreen](https://user-images.githubusercontent.com/79131217/184515857-46a4279a-b33e-4160-9271-de4cb04e91b7.PNG)

***
## インゲーム
インゲームは、前作からフィールドパートを削除していきなり敵との戦闘から始まります  
戦闘は敵を倒していくと次のフェーズに進み、現在最大で3フェーズあります  
またプレイヤーが最大で移動できる歩数の可視化や、スマートフォンで遊ぶことを意識したUIの設計など変更点が多々あります  
**前作**  
![battle](https://user-images.githubusercontent.com/79131217/184517238-072b35fd-5386-497d-8776-d83dcd9b9bcb.PNG)
![battle2](https://user-images.githubusercontent.com/79131217/184517239-62bef50d-0a45-4e0d-ac3c-edae66855243.PNG)  
**今作**  
![Field_0](https://user-images.githubusercontent.com/79131217/184515858-f5b0a2ba-cd70-42df-aa46-2b670b03edf6.PNG)
![Field_0_Move](https://user-images.githubusercontent.com/79131217/184515860-e44f9e6e-4ffc-4ea7-bde4-78a00f1e608e.PNG)
![Field_0_Fire](https://user-images.githubusercontent.com/79131217/184515859-23fc600a-a806-447d-a052-dd53bd48635c.PNG)

#### フェーズ2
![Field_1](https://user-images.githubusercontent.com/79131217/184515862-61099274-056c-4674-bec2-0f82cee1a06e.PNG)
#### フェーズ3
![Field_2](https://user-images.githubusercontent.com/79131217/184515863-a266415f-ee3a-4878-9437-23a06c086416.PNG)

#### 別ステージ(推奨レベル 60)
今作も状態異常があります  
>火傷：ターン開始時に小ダメージを受け、与ダメージが半減する。継続3ターン  
>麻痺：ダイスを振った際に出目が半減する。継続3ターン  
>氷：移動する際に通常の2倍出目を消費する。継続5ターン  
>毒：ターン開始時に小ダメージを受ける。また、移動時に極小ダメージを受ける。継続4ターン  
  
![intermediateBattle](https://user-images.githubusercontent.com/79131217/184515871-bd839322-3649-4c88-9569-12c22e7295f8.PNG)

#### 別ステージ(推奨レベル 100)
![FinalBattle](https://user-images.githubusercontent.com/79131217/184515864-8de5771f-3e25-4123-b951-6042176dbd57.PNG)

## 気を付けた部分・こだわった部分

### ユーザーが面白いと感じる要素を参考にしたゲームから見つける
>

### データベース
>

### UI
>

以上、三点がこだわった部分です。

## 感想
  
  
  
***
2022/08/14
