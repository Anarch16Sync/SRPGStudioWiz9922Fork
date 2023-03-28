# SRPGstudio用プラグイン
Plugins for SRPG Studio  

## 利用規約
・利用はSRPG Studioを使ったゲームに限ります  
・商用利用可  
・加工、再配布、転載OK (作成者を偽るのとスクリプトの販売は禁止)  
・著作表記と利用報告は任意  
・SRPG Studio利用規約は遵守してください  
http://srpgstudio.com/guide/rules.html  

## AIScoreDistance
AIが攻撃位置を決める要素に、距離などの位置関係を追加します。  
敵の無駄な動きがある程度改善されます。

## AISimpleForDifficulty
難易度によってAIを単純化させます。

## AttackLimitWeapon
攻撃専用または反撃専用の武器が作成できます。  

## AttributeSystem
属性によるダメージ変化を実装します。  
・必須はattribute-mainのみで、他はオブションです  
・デフォルトでは表示範囲の都合上、名称は2文字以内が望ましいです
* attribute-main
メイン処理
* attribute-attackwindow
 戦闘前ウィンドウに属性による威力上昇(↑)or低下(↓)を表示
* attribute-iteminfo
 アイテム情報ウィンドウに属性情報を追加
* attribute-terraininfo
 地形ウィンドウに属性情報を追加
* attribute-unitmenu
 ユニットメニューに属性耐性一覧のページを追加  

## AutoModeCommand
マップコマンドにオートモード(未行動の自軍全員が自動行動)を追加します。

## BattleItem
戦闘を発生させるアイテムを作成できます。

## BelongPanel
キャラチップの下に所属毎の色パネルを追加します。  
・PluginとMaterialをコピーすればそのまま使えます  
・別の画像を使用する場合はbelong-panel内で指定してください  
 通常は32*32の画像が自軍、敵軍、同盟軍の順に3つ並んだものです  
 ※ver1.123以降、「マップユニットシンボル」として同等の機能が公式に追加されました

## ChangeDifficulty
イベントから難易度を変更できます。  

## CustomSkillInvocationHide
発動時に表示しないカスタムスキルは、スキル情報ウィンドウで発動率が非表示になります

## EffectiveSkill
有効相手に対して常時特効となるスキルを作成できます(非発動型)

## ExperienceDistributionAdd
経験値分配画面に追加機能を実装します。

## ExperienceGaugeBar
経験値獲得画面をバー表示にします(UI画像を使用しないタイプ)

## ExtendTestTable
スイッチ調整と変数調整画面を変更します。

## FixedExp
マップ内の取得経験値を固定します。  
・戦闘経験値  
・アイテム使用時の経験値  
・スキル使用時の経験値  

## HpGaugeColor
HPゲージの色(画像)を残りHPによって変更します。

## ItemSynthesis
アイテム合成(ショップ)を作成します。  
現状は拠点のみ。  

## MapCursorEvent
マップカーソルで特定の位置を選択した時に発生するイベントを作成できます。

## MasterSkill
特定の武器タイプを装備している場合にボーナスを得ることができます。

## MessageEmotion
漫符など、メッセージ中の顔グラフィックや立ち絵に追加で画像を表示できます。

## NeutralUnit
指定スイッチがオンの時、同盟軍を中立軍として扱います。  
自軍と中立軍は互いに攻撃可能となります。

## NumberInputEvent
数値入力イベントを作成できます。

## PosessionLimitItem
武器(アイテム)タイプに所持個数制限を設定します。

## QuestRetreat
クエストマップに退却コマンド(拠点に戻る)を追加します。

## QuestSelectEvent
クエスト選択イベントを作成できます。

## RangeSkill
武器の射程を増減させるスキルを作成できます。

## ReinforceEvent
援軍を強制的に出現させるイベントを作成できます。

## ReplaceNpc
NPCの名前を表示する制御文字を追加します。

## SelectMenuDescription
アイテム、武器、杖の選択時にユニットメニュー同様の説明文を表示します。

## StockTrade
ストックの「全預け」を「交換」に変更します。

## SystemVariable
環境データにシステム変数を作成します。

## UnitItemSort
ユニットメニュー時、アイテムがソートできるようになります。

## UnitMenuPageChange
ユニットメニューが2ページ以上ある場合、ページ数を表示します。マウス対応

## UnknownHp
HPが一定以上の時は「???」で表示されるようになります。

## 連絡先
wiz  
twitter: https://twitter.com/wiz9922  
GitHub: https://github.com/wiz9922/SRPGstudio  
mail: wizjp22@gmail.com  

# Plugin for SRPGstudio
Plugins for SRPG Studio

## terms of service
・Use is limited to games using SRPG Studio
・Commercial use allowed
・Processing, redistribution, reprinting OK (impersonating the author and selling the script are prohibited)
・Copyright notation and usage report are optional
・Please comply with the SRPG Studio Terms of Use.
http://srpgstudio.com/guide/rules.html

## AIScoreDistance
Add positional relationships such as distance to the elements that determine the attack position of AI.
Enemy's useless movement is improved to some extent.

## AISimpleForDifficulty
Simplify the AI ​​by difficulty.

## AttackLimitWeapon
Weapons can be created for offensive or counterattack purposes.

## AttributeSystem
Implement damage change by attribute.
・Only attribute-main is required, the others are optional
・By default, it is desirable to use 2 characters or less for the name due to the display range.
*attribute-main
Main processing
*attribute-attack window
 Display power increase (↑) or decrease (↓) by attribute in the pre-battle window
*attribute-iteminfo
 Added attribute information to item info window
*attribute-terraininfo
 Added attribute information to terrain window
*attribute-unitmenu
 Added attribute resistance list page to unit menu

## AutoModeCommand
Add auto mode to map commands (all unacted units automatically act).

## Battle Items
You can create items that cause battle.

## BelongPanel
Add a color panel for each affiliation under the character chip.
・If you copy Plugin and Material, you can use it as it is
・If you want to use another image, please specify it in belong-panel
 Normally, 32*32 images are arranged in order of own army, enemy army, and allied army.
*Since ver1.123, the equivalent function has been officially added as "Map unit symbol"

## Change Difficulty
You can change the difficulty from the event.

## CustomSkillInvocationHide
For custom skills that are not displayed when activated, the activation rate will be hidden in the skill information window.

## Effective Skills
You can create a skill that is always effective against effective opponents (non-activation type)

## ExperienceDistributionAdd
Implement additional functions on the experience value distribution screen.

## ExperienceGaugeBar
Change the experience value acquisition screen to a bar display (type that does not use UI images)

## ExtendTestTable
Change switch adjustment and variable adjustment screens.

## Fixed Exp
Fixed the amount of experience gained in the map.
・Combat experience
・Experience points when using items
・Experience points when using skills

## HpGaugeColor
Change the color (image) of the HP gauge according to the remaining HP.

## Item Synthesis
Create an item synthesis (shop).
Currently only bases.

## MapCursorEvent
You can create an event that fires when a specific location is selected with the map cursor.

## Master Skills
You can get bonuses when equipping certain weapon types.

## Message Emotion
Images can be displayed in addition to face graphics and standing pictures in messages, such as comic symbols.

## NeutralUnit
When the designated switch is on, allied forces are treated as neutral forces.
Your army and neutral army can attack each other.

## NumberInputEvent
You can create numeric input events.

## PosessionLimitItem
Set the possession number limit for the weapon (item) type.

## QuestRetreat
Add a retreat command (return to base) to the quest map.

## QuestSelectEvent
You can create a quest selection event.

## Range Skill
You can create skills that increase or decrease weapon range.

## ReinforceEvent
You can create an event that forces reinforcements to appear.

## Replace Npc
Adds a control character that displays the NPC's name.

## SelectMenuDescription
Displays descriptions similar to the unit menu when selecting items, weapons, and staves.

## StockTrade
Change stock "all deposit" to "exchange".

## SystemVariable
Create a system variable in your environment data.

## UnitItemSort
Items can now be sorted in the unit menu.

## UnitMenuPageChange
Displays the number of pages if the unit menu has two or more pages. mouse support

## Unknown HP
When HP is above a certain level, it will be displayed as "???".

## contact address
wiz
twitter: https://twitter.com/wiz9922
GitHub: https://github.com/wiz9922/SRPGstudio
mail: wizjp22@gmail.com

