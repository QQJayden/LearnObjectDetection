# BlazePose

---

> 论文: 《**BlazePose: On-device Real-time Body Pose tracking**》

## 人体对齐

![1610338246668](assets/1610338246668.png)![1623056520287](assets/1623056520287.png)

## FC+hmp+offset

![1610338279985](assets/1610338279985.png)

关于blaze pose, 为啥

heatmap分支只是用来辅助loss计算，inference阶段不使用

训练阶段，regression分支，梯度不会反传给heatmap分支？