# bbScope [English](https://github.com/RealCorebb/bbScope/blob/main/README_EN.md "English")

![image](https://github.com/RealCorebb/bbScope/blob/main/IMG/bbScope.jpg?raw=true)

## 3D 多视角数码显微镜

很早以前就想拥有数码显微镜，所以我自己制作了一台，并设计了3D旋转模块，实现挺震撼的视觉效果。

### ▶️ 视频（制作过程、效果演示）：[YouTube](https://youtu.be/v0QcsWsoYbw "YouTube") ｜ [Bilibili](https://www.bilibili.com/video/BV1qtBBBwEWv "Bilibili")

## 目录结构

```text
CAD/                           # 3D模型
├── rotate.step                # CNC加工，模块旋转本体
├── bot.step                   # CNC加工，模块固定（与旋转体接触）
├── top.stl                    # 3D打印，模块固定（与镜头接触）
├── Mirror_3Dv2.stl            # 3D打印，反射镜固定
└── prism_cover.stl            # 3D打印，棱镜保护罩（非必须）
```

## 安装步骤

1. 将多颗定位销敲击塞入 `rotate.step` 对应孔位
2. 将多颗磁铁以一致的方向通过 T9000 胶水固定在 `rotate.step` 对应孔位
3. 将凹透镜用 T9000 胶水固定在 `rotate.step` 的圆心位置
4. 将 25×25×25mm 反射棱镜用 T9000 胶水固定在凹透镜下方的位置
5. 用 T9000 胶水将棱镜保护罩黏在反射棱镜上（非必须）
6. 将轴承敲进 `bot.step` 中，可用直径小于轴承外径的软垫放在中心，确保轴承敲进最深处
7. 将多颗定位销敲击塞入 `bot.step` 对应孔位
8. 将多颗磁铁以一致的反方向通过 T9000 胶水固定在 `bot.step` 对应孔位
9. `top.stl` 底部涂抹 T9000 胶水后，将 `bot.step` 连同轴承一起固定住
10. 将偏振片用 T9000 胶水黏在 `top.stl` 内部
11. 将 `top.stl` 顺着镜头内螺纹扭进去卡住
12. 将 `rotate.step` 通过磁吸卡进 `bot.step` 和 `top.stl` 整体的下方
13. 将 37×37×1mm 反射镜卡入 `Mirror_3Dv2.stl`
14. 将 `Mirror_3Dv2.stl` 通过两颗 M2 螺丝锁在 `rotate.step` 末端，另用两颗 M2 螺丝固定反射镜俯仰角度
15. 微调四颗 M2 螺丝，调整反射镜位置、俯仰角度、左右旋转角度，使同心度尽可能高

😄[爱发电(赞助)](https://afdian.com/a/kuruibb "爱发电(赞助)")   
🧵[Threads](https://www.threads.net/@coreoobb "@coreoobb") @coreoobb  
🐧QQ 群（仅供交流，人满请加Discord）：647186542  
😈Discord 频道：[加入](https://discord.gg/gvbcCtdQrk "加入")   
