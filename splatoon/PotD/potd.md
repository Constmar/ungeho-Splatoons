***Palace of the dead Radar***

  全ての階で表示される。
  Distance Limitはなし（0-100m）

* Target Sensing Range

  ターゲット対象を中心に、緑色の半径 target hitbox + 10m　の円を表示
  ターゲットしている敵の感知範囲の簡易的な目安

* Mimic Sensing Range

  ミミックを中心に、黄色の半径 target hitbox + 14m の円を表示
  ミミックの感知範囲の目安

* Mandragora Sensing Range

  ピグマイオイを中心に、水色の半径 target hitbox + 14m の円を表示
  敵変化によるピグマイオイ出現の目安

* Turning Enemies

  ターゲット対象を中心に、水色の半径 1.5m の円を表示
  敵回しの目安

* Metastasis Tracker

  自身と転移の石塔を結ぶ赤色の直線を表示
  転移の石塔を中心に、赤色の半径 2m の円を表示
  転移の石塔の場所の目安
  always pixel perfect（足元のdot）が表示された円に入ると転移が開始される

* Treasure Chest Gold

  金箱を中心に、白色の半径 target hitbox + 4m の円を表示
  金箱の場所の目安
  always pixel perfect（足元のdot）が表示された円に入ると取得可能

* Treasure Chest Silver

  銀箱を中心に、青色の半径 target hitbox + 4m の円を表示
  銀箱の場所の目安
  always pixel perfect（足元のdot）が表示された円に入ると取得可能

* Treasure Chest Bronze(2,3,5,6,7,8,9,10,11,12,13)

  銅箱を中心に、橙色の半径 target hitbox + 2.5m の円を表示
  銅箱の場所の目安
  always pixel perfect（足元のdot）が表示された円に入ると取得可能（正確でない）

* Treasure Chest Bronze4(MiMic)

  銅箱(ミミック)を中心に、水色の半径 target hitbox + 2.5m の円を表示
  銅箱（ミミック）の場所の目安
  always pixel perfect（足元のdot）が表示された円に入ると取得可能（正確でない）

* Morphological change Range

  自身を中心に、水色の半径 your hitbox + 18m の円を表示
  形態変化のレンジの目安（敵のターゲットサークルが円に触れていれば有効）

* stepped on the trap

  トラップを踏んだ跡地を中心に、紫色の半径 0.5m の円を表示
  （銀箱を開けた跡地にも表示される）

* always pixel perfect

  自身を中心に、緑色の半径 0m の円を表示（ドット）
  hitboxの目安として常に表示される

* Contact Range

  自身を中心に、赤色の your hitbox + 0.55m の円を表示
  円が敵の中心に触れたら接触判定として感知されてもおかしくはないくらいの目安（あまり正確ではない）
  接触扱いで感知される範囲は、ターゲットサークルの大きさに関わらず敵によってバラバラ

* Trap Hitbox

  自身を中心に、緑色の your hitbox + 1.2m の円を表示
  罠に接触するかの目安
  表示された円が、Deep Dungeon Helper プラグインによって表示された点に触れると、その場所に罠が存在した場合は起爆する。

```
~Lv2~{"Name":"Palace of The Dead Radar","Group":"Palace of The Dead ","ZoneLockH":[593,561,562,563,564,565,594,595,596,597,598,599,600,601,602,603,604,605,606,607],"ElementsL":[{"Name":"Target Sensing Range","type":1,"radius":10.0,"color":3355508512,"refActorType":2,"includeHitbox":true},{"Name":"Mimic Sensing Range","type":1,"radius":14.0,"color":3355497983,"refActorNPCNameID":2566,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Mandragora Sensing Range","type":1,"radius":14.0,"color":3370974976,"refActorNPCNameID":5041,"refActorComparisonType":6,"includeHitbox":true},{"Name":"Turning Enemies","type":1,"radius":1.5,"color":3372023552,"refActorType":2},{"Name":"Metastasis Tracker","type":1,"radius":2.0,"overlayText":"転移の石塔","refActorDataID":2007188,"refActorComparisonType":3,"includeRotation":true,"tether":true},{"Name":"Treasure Chest Gold","type":1,"radius":4.0,"color":3372220415,"overlayText":"Gold Chest","refActorDataID":2007358,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Silver","type":1,"radius":4.0,"color":3372158208,"overlayText":"Silver Chest","refActorDataID":2007357,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":802,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze2","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":804,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze3","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":784,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze4(Mimic)","type":1,"radius":2.5,"color":3371433728,"overlayText":"Mimic","refActorDataID":2006020,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze5","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":785,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze6","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":786,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze7","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":788,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze8","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":789,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze9","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":790,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze10","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":803,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze11","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":783,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze12","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":787,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Treasure Chest Bronze13","type":1,"radius":2.5,"color":3355496447,"overlayText":"Bronze Chest","refActorDataID":782,"refActorComparisonType":3,"includeHitbox":true},{"Name":"Morphological change Range","type":1,"radius":18.0,"color":3372217088,"refActorType":1,"includeOwnHitbox":true},{"Name":"stepped on the trap","type":1,"radius":0.5,"color":3372024063,"overlayText":"stepped on the trap","refActorModelID":480,"refActorComparisonType":1},{"Name":"always pixel perfect","type":1,"radius":0.0,"color":3357277952,"refActorType":1},{"Name":"Contact Range","type":1,"radius":0.55,"refActorType":1,"includeOwnHitbox":true},{"Name":"Trap Hitbox","type":1,"radius":1.2,"color":3355508480,"refActorType":1,"includeOwnHitbox":true}]}
```
