* The unending coil of bahamud

  [JP]トリガーのセリフや敵の名前は日本語で設定されています。

  必要なものをオンにして使ってください。

```
~Lv2~{"Name":"ツインタニア","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"ElementsL":[{"Name":"ツインタニア(距離15m)","type":1,"radius":15.0,"color":3355508496,"refActorNPCNameID":1482,"FillStep":5.0,"refActorComparisonType":6,"onlyTargetable":true,"onlyVisible":true},{"Name":"ツインタニア(距離20m)","type":1,"radius":20.0,"color":3372158464,"refActorNPCNameID":1482,"refActorComparisonType":6,"onlyTargetable":true,"onlyVisible":true},{"Name":"魔力錬成","type":1,"radius":7.0,"color":3369795328,"thicc":4.0,"overlayText":"魔力錬成","refActorComparisonType":7,"refActorVFXPath":"vfx/lockon/eff/bahamut_maryokukyu_target_01i.avfx","refActorVFXMax":10000},{"Name":"ファイアボール","type":1,"radius":3.45,"Donut":0.5,"color":3372218624,"overlayTextColor":3369795328,"thicc":4.0,"overlayText":"Stack","refActorComparisonType":7,"refActorVFXPath":"vfx/lockon/eff/bahamut_kakyu_target_t01i.avfx","refActorVFXMax":5000},{"Name":"魔力圧縮体","type":1,"radius":0.0,"refActorNPCNameID":2210,"refActorObjectLife":true,"refActorLifetimeMin":0.0,"refActorLifetimeMax":10.0,"refActorComparisonType":6,"includeHitbox":true}]}
~Lv2~{"Name":"ツイスター（警告）","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ツイスター（警告）","type":1,"radius":0.5,"color":3355508509,"overlayTextColor":3355506192,"overlayText":"ツイスター","refActorPlaceholder":["<1>","<2>","<3>","<4>","<5>","<6>","<7>","<8>"],"refActorComparisonType":5,"includeOwnHitbox":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":1.7,"MatchIntl":{"Jp":"ツインタニアは「ツイスター」の構え。"}}]}
~Lv2~{"Name":"ツイスター(設置)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ツイスターの場所","type":1,"radius":0.0,"color":1174470429,"refActorDataID":6358,"refActorComparisonType":3,"includeHitbox":true,"includeOwnHitbox":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":7.0,"MatchIntl":{"Jp":"ツインタニアの「ツイスター」"},"MatchDelay":0.2}]}
~Lv2~{"Name":"ネール","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"ElementsL":[{"Name":"メガフレアダイブ","type":3,"offY":50.0,"radius":6.0,"color":4278190335,"refActorNPCID":3210,"refActorRequireCast":true,"refActorCastId":[9953],"FillStep":1.0,"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"ルナダイブ","type":3,"offY":50.0,"radius":4.0,"color":4278190335,"thicc":5.5,"refActorNPCID":2612,"refActorRequireCast":true,"refActorCastId":[9923],"FillStep":1.0,"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"ツイスターダイブ","type":3,"offY":50.0,"radius":4.0,"color":838861055,"refActorNPCID":1482,"refActorRequireCast":true,"refActorCastId":[9906],"FillStep":1.0,"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"カータライズ(ダークテイル)","type":3,"offY":47.14,"radius":10.0,"color":838861055,"thicc":4.2,"refActorNPCID":6958,"refActorRequireCast":true,"refActorCastId":[9931,9932,9933,9934,9935],"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"カータライズ（ライトファング）","type":3,"offY":47.14,"radius":10.0,"color":838861055,"thicc":4.2,"refActorNPCID":6957,"refActorRequireCast":true,"refActorCastId":[9931,9932,9933,9934,9935],"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"カータライズ（ファイアホーン）","type":3,"offY":47.14,"radius":10.0,"color":838861055,"thicc":4.2,"refActorNPCID":2630,"refActorRequireCast":true,"refActorCastId":[9931,9932,9933,9934,9935],"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"カータライズ（サンダーウィング）","type":3,"offY":47.14,"radius":10.0,"color":838861055,"thicc":4.2,"refActorNPCID":2632,"refActorRequireCast":true,"refActorCastId":[9931,9932,9933,9934,9935],"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"カータライズ（アイスクロウ）","type":3,"offY":47.14,"radius":10.0,"color":838861055,"thicc":4.2,"refActorNPCID":2631,"refActorRequireCast":true,"refActorCastId":[9931,9932,9933,9934,9935],"refActorComparisonType":4,"includeRotation":true,"Filled":true},{"Name":"雷散開","type":1,"radius":5.0,"color":1191116936,"refActorPlaceholder":["<1>","<2>","<3>","<4>","<5>","<6>","<7>","<8>"],"refActorRequireBuff":true,"refActorBuffId":[466],"refActorComparisonType":5,"Filled":true},{"Name":"死の宣告","type":1,"radius":0.53,"color":3357277952,"overlayTextColor":3356884736,"thicc":4.0,"overlayText":"死の宣告","refActorPlaceholder":["<1>","<2>","<3>","<4>","<5>","<6>","<7>","<8>"],"refActorCastTimeMax":6.0,"refActorRequireBuff":true,"refActorBuffId":[210,910,1738,1769,1970,2516,2519,2976,3364],"refActorUseBuffTime":true,"refActorBuffTimeMax":6.0,"refActorComparisonType":5},{"Name":"ファイアホーン(デバフ)","type":1,"overlayTextColor":3355443455,"overlayVOffset":0.4,"thicc":4.0,"overlayText":"ファイアホーン","refActorPlaceholder":["<1>","<2>","<3>","<4>","<5>","<6>","<7>","<8>"],"refActorRequireBuff":true,"refActorBuffId":[464],"refActorComparisonType":5}]}
~Lv2~{"Name":"ネール（ファイアホーン1回目）","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ファイアホーン(全員)","type":1,"radius":3.8,"Donut":0.2,"color":3371433728,"overlayTextColor":3371433728,"thicc":4.0,"overlayText":"全員","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"ネール・デウス・ダーナスの「龍神の加護」"},"MatchDelay":13.0}]}
~Lv2~{"Name":"ネール（ファイアホーン2回目）","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ファイアホーン（1人受け）","type":1,"radius":4.0,"overlayTextColor":3355443455,"thicc":4.0,"overlayText":"1人受け","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"ネール・デウス・ダーナスの「龍神の加護」"},"MatchDelay":28.0}]}
~Lv2~{"Name":"ネール（ファイアホーン3回目）","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ファイアホーン（ファイアホーン持ち以外）","type":1,"radius":4.0,"Donut":0.2,"color":3355508719,"overlayTextColor":3355508719,"overlayVOffset":0.88,"thicc":3.8,"overlayText":"ファイアホーン以外","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"赤熱し、焼かれし道を 鉄の覇道と成す！"},"MatchDelay":17.0},{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"赤熱せし 月の祝福を！"},"MatchDelay":17.0}]}
~Lv2~{"Name":"ネール（ファイアホーン4回目）","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ファイアホーン（全員）","type":1,"radius":3.8,"Donut":0.2,"color":3371433728,"overlayTextColor":3371433728,"thicc":4.0,"overlayText":"全員","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"我、舞い降りて 鉄の覇道を征く！"},"MatchDelay":7.0},{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"我、舞い降りて 月を仰がん！"},"MatchDelay":7.0}]}
~Lv2~{"Name":"ネール台詞分岐1回目：確定ダイナモ→頭割り(1)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ダイナモ","type":1,"radius":5.7,"Donut":20.0,"color":3355508558,"thicc":4.0,"refActorNPCID":2612,"FillStep":1.0,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"月よ！ 赤熱し、神敵を焼け！"}}]}
~Lv2~{"Name":"ネール台詞分岐1回目：確定ダイナモ->頭割り(2)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"頭割り","type":1,"radius":3.8,"Donut":0.2,"color":3372220160,"overlayTextColor":3372220160,"thicc":4.0,"overlayText":"Stack","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":4.0,"MatchIntl":{"Jp":"月よ！ 赤熱し、神敵を焼け！"},"MatchDelay":5.0}]}
~Lv2~{"Name":"ネール台詞分岐1回目：確定ダイナモ→チャリオット(1)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ダイナモ","type":1,"radius":5.7,"Donut":20.0,"color":3355508558,"thicc":4.0,"refActorNPCID":2612,"FillStep":1.0,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"月よ！ 鉄の覇道を照らせ！"}}]}
~Lv2~{"Name":"ネール台詞分岐1回目：確定ダイナモ→チャリオット(2)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"チャリオット","type":1,"radius":10.0,"color":840302336,"refActorNPCID":2612,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"MatchIntl":{"Jp":"月よ！ 鉄の覇道を照らせ！"},"MatchDelay":6.0}]}
~Lv2~{"Name":"ネール台詞分岐2回目：確定頭割り→チャリオット(1)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"頭割り","type":1,"radius":3.8,"Donut":0.2,"color":3372220160,"overlayTextColor":3372220160,"thicc":4.0,"overlayText":"Stack","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"赤熱し、焼かれし道を 鉄の覇道と成す！"}}]}
~Lv2~{"Name":"ネール台詞分岐2回目：確定頭割り→チャリオット(2)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"チャリオット","type":1,"radius":10.0,"color":840302336,"refActorNPCID":2612,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"MatchIntl":{"Jp":"赤熱し、焼かれし道を 鉄の覇道と成す！"},"MatchDelay":6.0}]}
~Lv2~{"Name":"ネール台詞分岐2回目：確定頭割り→ダイナモ(1)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"頭割り","type":1,"radius":3.8,"Donut":0.2,"color":3372220160,"overlayTextColor":3372220160,"thicc":4.0,"overlayText":"Stack","refActorType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"赤熱せし 月の祝福を！"}}]}
~Lv2~{"Name":"ネール台詞分岐2回目：確定頭割り→ダイナモ(2)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ダイナモ","type":1,"radius":5.7,"Donut":20.0,"color":3355508558,"thicc":4.0,"refActorNPCID":2612,"FillStep":1.0,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"MatchIntl":{"Jp":"赤熱せし 月の祝福を！"},"MatchDelay":6.0}]}
~Lv2~{"Name":"ネール台詞分岐3回目：確定小散開→チャリオット(1)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ダイブ","type":1,"radius":3.2,"color":840695552,"refActorPlaceholder":["<1>","<2>","<3>","<4>","<5>","<6>","<7>","<8>"],"refActorComparisonType":5,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"我、舞い降りて 鉄の覇道を征く！"}}]}
~Lv2~{"Name":"ネール台詞分岐3回目：確定小散開→チャリオット(2)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"チャリオット","type":1,"radius":10.0,"color":840302336,"refActorNPCID":2612,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"MatchIntl":{"Jp":"我、舞い降りて 鉄の覇道を征く！"},"MatchDelay":6.0}]}
~Lv2~{"Name":"ネール台詞分岐3回目：確定小散開→ダイナモ(1)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ダイブ","type":1,"radius":3.2,"color":840695552,"refActorPlaceholder":["<1>","<2>","<3>","<4>","<5>","<6>","<7>","<8>"],"refActorComparisonType":5,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"MatchIntl":{"Jp":"我、舞い降りて 月を仰がん！"}}]}
~Lv2~{"Name":"ネール台詞分岐3回目：確定小散開→ダイナモ(2)","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"ダイナモ","type":1,"radius":5.7,"Donut":20.0,"color":3355508558,"thicc":4.0,"refActorNPCID":2612,"FillStep":1.0,"refActorComparisonType":4,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"MatchIntl":{"Jp":"我、舞い降りて 月を仰がん！"},"MatchDelay":6.0}]}
~Lv2~{"Name":"UCOB First exaflare safe line","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":3,"refY":-2.0,"offY":60.0,"radius":2.0,"color":1174470400,"thicc":4.0,"refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"FillStep":2.0,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":18.0,"IntervalBetweenFreezes":0.5}
~Lv2~{"Name":"UCOB Exaflare only first - 1","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":1,"radius":6.0,"color":1342242815,"overlayBGColor":1879048447,"overlayTextColor":4278190080,"overlayFScale":3.0,"overlayText":"--- FIRST ---","refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":4.0,"IntervalBetweenFreezes":0.5}
~Lv2~{"Name":"UCOB Exaflare only first - 2","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":1,"offY":8.0,"radius":6.0,"color":1342242815,"refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":5.7,"IntervalBetweenFreezes":0.5}
~Lv2~{"Name":"UCOB Exaflare only first - 3","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":1,"offY":16.0,"radius":6.0,"color":1342242815,"refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":7.2,"IntervalBetweenFreezes":0.5}
~Lv2~{"Name":"UCOB Exaflare only first - 4","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":1,"offY":24.0,"radius":6.0,"color":1342242815,"refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":8.7,"IntervalBetweenFreezes":0.5}
~Lv2~{"Name":"UCOB Exaflare only first - 5","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":1,"offY":32.0,"radius":6.0,"color":1342242815,"refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":10.2,"IntervalBetweenFreezes":0.5}
~Lv2~{"Name":"UCOB Exaflare only first - 6","Group":"The Unending Coil of Bahamud-Ultimate","ZoneLockH":[733],"DCond":5,"ElementsL":[{"Name":"","type":1,"offY":40.0,"radius":6.0,"color":1342242815,"refActorNPCNameID":3210,"refActorRequireCast":true,"refActorCastId":[9968],"refActorUseCastTime":true,"refActorCastTimeMax":0.25,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":3.0,"Match":"(3210>9967)"}],"Freezing":true,"FreezeFor":11.7,"IntervalBetweenFreezes":0.5}
```


<!-- 
公式のプリセットから、恐らくカータライズ

```
<https://github.com/PunishXIV/Splatoon/raw/main/SplatoonScripts/Duties/Stormblood/UCOB%20dragon%20baits.cs>
```


公式のプリセットから、恐らく天地の三重奏
優先度の設定を行う必要がある。

```
https://github.com/PunishXIV/Splatoon/raw/main/SplatoonScripts/Duties/Stormblood/UCOB%20Heavensfall%20Trio%20Towers.cs
```


-->