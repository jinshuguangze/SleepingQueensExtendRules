# SleepingQueensExtendRules

 经典桌游《睡皇后》的一套新规则，在不改变原版桌游的情况下极大的扩展玩法。

## 数字牌

将数字牌单张或者组合打出可以抽牌，规则为：
- 打出单张数字牌：抽一张牌。
- 打出两张及以上相同点数的数字牌：抽取打出数量的牌。
- 打出数字牌的点数组合满足以下公式之一（字母代表任意数字牌），抽取打出数量的牌：
  1. a+b=c
  2. a+b+c=d
  3. a+b=c+d
  4. a+b+c+d=e
  5. a+b+c=d+e 

## 能力牌

- 骑士牌：在以下两种阶段中可打出此牌，抢夺并`拥有`任意玩家（包括自己）的皇后牌；抽一张牌：
  - 在任意公主被`唤醒`后。
  - 你的回合中。

![Knight](/img/knight.jpg)

- 龙牌：有两种方式打出此牌：
  - 当任意玩家（包括自己）打出骑士牌时，使那张骑士牌失效；抽一张牌。
  - 在你的回合中，将龙牌视作任意数字牌打出。

![Dragon](/img/dragon.jpg)

- 药水牌：有两种方式打出此牌：
  - 当任意玩家（包括自己）打出龙牌时，使那张龙牌失效；抽一张牌。
  - 在你的回合中，打出此牌将任意玩家（包括自己）`拥有`的皇后牌翻盖回到皇后区的任意空位；抽一张牌。

![Potion](/img/potion.jpg)

- 魔杖牌：有两种方式打出此牌：
  - 当任意玩家（包括自己）打出药水牌时，使那张药水牌失效；抽一张牌。
  - 在你的回合中，打出此牌将任意玩家（包括自己）`拥有`的皇后牌与皇后区任意皇后牌交换。

![Wand](/img/wand.jpg)

- 小丑牌：`揭示`并抽取一张牌，如果该牌为数字牌，则从你开始，顺时针数数字牌的点数，最后指向的玩家`揭示`并`拥有`皇后区中的一张皇后牌。

![Jester](/img/jester.jpg)

## 皇后牌

- Pancake Queen：该皇后牌在初始摆放时正面朝上。

![Pancake Queen](/img/pancake%20queen.jpg)

- Cake Queen：当你`拥有`该皇后牌时，翻盖你`拥有`的所有皇后牌。

![Cake Queen](/img/cake%20queen.jpg)

- Ladybug Queen：骑士牌无法抢夺该皇后牌。

![Ladybug Queen](/img/ladybug%20queen.jpg)

- Peacock Queen：药水牌无法沉睡该皇后牌。

![Peacock Queen](/img/peacock%20queen.jpg)

- Rainbow Queen：该皇后牌在`胜利判定`时，数量被视作两张。

![Rainbow Queen](/img/rainbow%20queen.jpg)

- Rose Queen：当该牌被`唤醒`时，可再`唤醒`一张其他皇后牌。

![Rose Queen](/img/rose%20queen.jpg)

- Heart Queen：当你同时`拥有`Heart Queen与任意分数值为5的皇后时，必须选择其一：
  - 将Heart Queen翻盖回皇后区任意空位。
  - 将所有分数值为5的皇后翻盖回皇后区任意空位。

![Heart Queen](/img/heart%20queen.jpg)

- Cat Queen：当你同时`拥有`Dog Queen和Cat Queen时，必须选择其中一张翻盖回皇后区任意空位。

![Cat Queen](/img/cat%20queen.jpg)

- Dog Queen：当你同时`拥有`Dog Queen和Cat Queen时，必须选择其中一张翻盖回皇后区任意空位。

![Dog Queen](/img/dog%20queen.jpg)

- Sunflower Queen：当你同时`拥有`Starfish Queen，Moon Queen和Sunflower Queen时，立刻获得游戏胜利。

![Sunflower Queen](/img/sunflower%20queen.jpg)

- Moon Queen：当你同时`拥有`Starfish Queen，Moon Queen和Sunflower Queen时，立刻获得游戏胜利。

![Moon Queen](/img/moon%20queen.jpg)

- Starfish Queen：当你同时`拥有`Starfish Queen，Moon Queen和Sunflower Queen时，立刻获得游戏胜利。

![Starfish Queen](/img/starfish%20queen.jpg)

## 国王牌

- Puzzle King：`揭示`并`唤醒`一张皇后牌；在`本轮次`内，所有玩家如果打出数字牌，则只能单张；抽一张牌。

![Puzzle King](/img/puzzle%20king.jpg)

- Bubble Gum King：`揭示`最多三张皇后牌，选择一张皇后牌`唤醒`，其余两张皇后牌翻转回去；抽一张牌。

![Bubble Gum King](/img/bubble%20gum%20king.jpg)

- Chess King：`揭示`并`唤醒`一张皇后牌；由你在奇数数字牌或偶数数字牌中选择一种，在`本轮次`内，所有玩家无法打出此种类数字牌；抽一张牌。

![Chess King](/img/chess%20king.jpg)

- Hat King：`揭示`并`唤醒`一张皇后牌；可选择任意一名玩家（包括自己）`拥有`的一张皇后牌，将这张皇后牌与所有受到Hat King影响而被`唤醒`的皇后牌（在本规则下，除了Rose Queen以外，只可能为一张）翻盖并洗混，让那名被选择的玩家抽取并`拥有`一张皇后牌，你则`拥有`剩余的皇后牌；抽一张牌。

![Hat King](/img/hat%20king.jpg)

- Cookie King：`揭示`一张皇后牌，
  - 如果这张皇后牌是Pancake Queen，则翻转所有皇后区的皇后牌；`唤醒`Pancake Queen；抽一张牌。
  - 如果这张皇后牌是Cake Queen，则翻盖所有玩家`拥有`的皇后牌；`唤醒`Cake Queen；抽一张牌。
  - 如果都不是，则`唤醒`这张皇后牌；抽一张牌。

![Cookie King](/img/cookie%20king.jpg)

- Tie-Dye King：`揭示`一张皇后牌，`判定过程`：
  - 如果该皇后牌的背景颜色为红色，玩家可选择是否继续`揭示`另一张皇后牌
    - 如果玩家选择继续`揭示`，则重复`判定过程`。
    - 如果玩家放弃继续`揭示`或者场上皇后牌已被全部`揭示`，则终止`判定过程`；按照已`揭示`皇后的先后顺序`唤醒`皇后；抽一张牌。
  - 如果该皇后牌的背景颜色为绿色，则终止`判定过程`；翻盖所有被`揭示`的皇后牌；抽一张牌。
  - 如果该皇后牌的背景颜色为其他颜色，则终止`判定过程`；按照已`揭示`皇后的先后顺序`唤醒`皇后；抽一张牌。

![Tie-Dye King](/img/tie-dye%20king.jpg)

- Fire King：`揭示`并`唤醒`一张皇后牌；抽一张牌；可选择场上所有玩家（包括自己）的最多总计五张手牌，永久移出该局游戏（不参与后续的洗牌），并使之分别抽取损失牌的张数。

![Fire King](/img/fire%20king.jpg)

- Turtle King：`揭示`并`唤醒`一张皇后牌；抽取并`揭示`一张牌；如果该牌为数字牌且小于等于5，则由你再进行一回合。

![Turtle King](/img/turtle%20king.jpg)

## 特殊

- 由于骑士牌的效果是直接`拥有`皇后牌，故无法在当回合立即被其他骑士牌/药水牌立即抢夺/沉睡。

- 当魔杖牌使用交换效果打出时，保留两张被交换的卡牌的翻盖状态和位置，也就是说假如魔杖交换的皇后区的皇后牌是正面朝上的，魔杖交换过去的玩家的皇后牌也必须正面朝上放置到皇后区。并且魔杖牌的交换效果无法触发皇后牌的`唤醒`。

- 由于小丑牌的效果是直接`拥有`皇后牌，故无法在当回合立即被骑士牌/药水牌立即抢夺/沉睡。

- 当Chess King发动效果时，如果一名玩家手牌受到效果限制无法打出任何牌，则跳过该玩家回合。

- 一个比较复杂的情况：当玩家A打出Hat King`唤醒`并`揭示`Rose Queen，由于Rose Queen的`唤醒`效果，玩家A立即`唤醒`并`揭示`另一张皇后牌，这时`唤醒`了Dog Queen，但玩家A此时已经`拥有`了Cat Queen，正常来讲，Dog Queen在`拥有`后会被重新翻盖并放置回皇后区内，为了避免这种情况，玩家A使用Hat King的可选择效果，将所有因Hat King影响而`唤醒`的皇后牌（在此即Rose Queen和Dog Queen）与指定一名玩家B所`拥有`的一张皇后牌都翻盖并洗混，由玩家B来选择一张翻盖的皇后牌`拥有`，其余皇后牌则玩家A`拥有`。这样如果玩家B选择了Dog Queen，则可`拥有`玩家B的那张皇后牌，避免了Dog Queen的负面效果；如果玩家B选择了Rose Queen，则可`拥有`玩家B的那张皇后牌（大多比起Rose Queen分数更高或者有额外效果）；即使玩家B选择了他自己原本的那张皇后牌，那也仅仅是和Hat King发动效果前没有任何变化而已。

- 当Cookie King`揭示`Pancake Queen后，翻转的效果是指：如果皇后牌是翻盖的，则变为正面朝上的，如果皇后牌是正面朝上的，则变为翻盖的。如果某张皇后牌后面因为药水牌或者其他方法再次回到皇后区，则仍会正常翻盖放置；当Cookie King`揭示`Cake Queen后，或者玩家`拥有`Cake Queen后，翻盖`拥有`的皇后牌是指：可以自由洗混`拥有`的皇后牌，并且当被其他玩家选中时（骑士牌抢夺，药水牌沉睡，国王牌特殊能力选择等），其他玩家只能抽取这些翻盖的皇后牌。

- 当多名皇后牌被一名玩家同时`拥有`后，如果这些皇后牌的拥有效果产生冲突（比如Dog Queen和Cat Queen），那么可以由玩家自由选择翻盖回皇后区的皇后，直到不会产生冲突为止。

- 背景颜色为红色的皇后牌为Pancake Queen，Cake Queen，Starfish和Cat Queen（由于印刷关系，Cat Queen可能表现得没那么红色，但是实际上确实背景颜色是红色的）；背景颜色为绿色的皇后牌为Ladybug Queen，Rose Queen，Heart Queen和Dog Queen；背景颜色为其他的皇后牌为Peacock Queen，Rainbow Queen，Sunflower Queen和Moon Queen。

- 当一名玩家需要抽牌时，受到Fire King移出卡牌的效果影响，`抽牌堆`和`弃牌堆`均已无牌，则计算所有玩家`拥有`皇后牌的分数和，分数高者获胜；如果有分数相同的，则计算`拥有`皇后牌的数量，数量多者获胜；如果数量相同，则他们共同胜利。
