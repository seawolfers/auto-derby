# auto-derby

自动化养马

2021-06-01: 气槽 3 速 2 智 1 体 自动养成结果为 10300 分 URA 冠军，历代评价点第一，无手动干预

2021-05-31: 麦昆 3 速 2 智 1 体 自动养成结果为 9100 分 URA 冠军，第一年手动出战一次

2021-05-30: 气槽 3 速 2 智 1 体 自动养成结果为 9800 分 URA 冠军，历代评价点第二，无手动干预

2021-05-30: 大和赤骥 3 速 2 智 1 体 自动养成结果为 9300 分 URA 冠军，第一年手动出战一次

## 功能

- [x] 团队赛
  - [ ] 有胜利确定奖励时吃帕菲 (需要我遇到奖励才能着手实现)
- [x] 日常赛
- [x] 传奇赛
  - [x] 自动领奖励
- [x] 遇到限时商店自动买空
- [x] 育成
  - [x] 根据当前属性选择训练
  - [x] 遇到新事件选项请求人工处理，后续相同事件使用相同选择
  - [x] 根据训练效果选择训练
  - [x] 给暑期集训保留体力
  - [ ] 自动出赛适应性匹配的 G1
  - [ ] 自动选择比赛跑法（较短距离无脑逃）

## 使用方法

需求 DMM 版 和 python3.8

安装依赖

```shell
py -3.8 -m pip install -r requirements.txt
```

双击 `launcher.cmd` 可通过一个简单的 GUI 进行启动

或者手动调用模块：

```shell
py -3.8 -m auto_derby 工作名称
```

工作名称随便输入错误的名字会提示当前支持的工作
