第七周更新：

演示视频：https://share.weiyun.com/ANOuA6Ec



------



第六周更新：

演示视频：https://share.weiyun.com/FkECD7Mq

完成的内容：

* 实现了脚印
* 制作了可拾取的枪械（步枪和手雷），其采用低频率主动检测
* 实现了手雷的发射，手雷速度降到一定程度或命中Character时会爆炸

额外完成的内容：重做了部分动画，实现了武器的切换等

没有完成的内容：没有加音效，步枪的开火还没做



------



第五周更新：

演示视频：https://share.weiyun.com/tiNEiGlO

完成的内容：

* 实现了角色的Idle、移动、跳跃动画
* 实现角色的射击，角色瞄准时会有俯仰表现，且角色的手臂会一直指向子弹的预计击中点
* 按F键播放一个动作，如果角色在移动则腿部是走路表现，否则腿部依然是动画表现
* 按下Alt键时，角色不随视角旋转而旋转，松开时恢复原视角

额外完成的内容：

* 角色开始瞄准时会切换至越肩视角，这是用AnimNotify实现的

其他说明：动画采用的是虚幻争霸中的Wraith，但是他的所有动作都是手持步枪的，所以我只采用了其下半身的动画和原来的动画融合（这个角色的动画素材比较奇怪，比如向左跑的表现实际是向右后退，以及动画的朝向全都转过了一个90度，我通过添加关键帧修复了这个问题）。



-------



第四周更新：

完成的内容是添加基本操作的UI，还没有实现SaveGame。

额外完成的内容是给角色添加了TPS的瞄准方式，角色会射击准星指向的位置。

演示视频（两个）：https://share.weiyun.com/wZAKO20A

第一个视频主要演示了射击操作的手感。

第二个视频演示了触屏的UI操作模式。

上传的版本是第二个视频的版本。



-------



演示视频：https://share.weiyun.com/Wqg7yieA



添加的内容是一类悬浮的方块，场景中共有两个，击中运动的得两分，击中静止的得一分。

当第二个玩家加入对局时，屏幕上方会开始显示计时，计时结束时会根据玩家的比分结算并显示不同的游戏结束画面。

此外给人物添加了移动和跳跃。
