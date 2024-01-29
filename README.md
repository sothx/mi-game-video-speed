# mi-game-video-speed

## 模块简介
该Magisk模块用于补全小米部分旗舰、新机型下开启三倍数进游戏的新功能体验。

标准版：
- 仅开启小米已适配的三倍数进游戏中的游戏白名单。

特别版:
- 让更多游戏支持三倍数进游戏（可能有预料之外的问题）

## 模块都做了什么？

通过修改build.prop补全以下系统体验:

- 开启三倍数进游戏的新功能
```bash
debug.game.video.support=true
debug.game.video.speed=true
```
- 让更多游戏支持三倍数进游戏
```bash
debug.performance.tuning=1
video.accelerate.hw=1
debug.sf.hw=1
```


## 其他

有关模块库的更多信息请查看Github (https://github.com/sothx/mi-game-video-speed)
