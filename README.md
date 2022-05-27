# [文章](https://zong4.github.io/2022/05/22/SpaceCollider/)

<img src="https://zong4.top/gallery/picture/source/Game.png" width="700px" title="游戏界面">

# 视频

<video src="https://zong4.github.io/gallery/media/source/SpaceCollider.mp4" width="700px" controls="controls"></video>

# [图片](https://zong4.github.io/2022/05/22/SpaceCollider/)

# 背景

太空漫游hh。

# 玩法

通过碰撞来让对方掉下去死亡（无血条），每人两条命，部分操作设置可在设置界面修改。

# 实现

- 主界面有开场动画和基础的UI；
- 设置界面可以自定义更改设置；
- 地图为随机生成；
- 添加了几种技能以及子弹，玩家自主选择携带；
- 人物实现分机控制（一台电脑一个人物，目前房间最多支持4人），可以实现多段跳（自定义），有完善的行走跳跃等动画；
- 子弹射击爆炸有相应的音效和动画。
- 陨石以及玩家射出的子弹的生命周期均与房间的相同（为主机创建）；
