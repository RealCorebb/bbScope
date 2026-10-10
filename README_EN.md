# bbScope [中文](https://github.com/RealCorebb/bbScope/blob/main/README.md "中文")

![image](https://github.com/RealCorebb/bbScope/blob/main/IMG/bbScope.jpg?raw=true)

## 3D Multi-Angle Digital Microscope

I have wanted to own a digital microscope for a long time, so I built one myself and designed a 3D rotating module to achieve stunning visual effects.

### ▶️ Videos (Build Process & Demo): [YouTube](https://www.youtube.com/watch?v=Ltk5rLHQRfw "YouTube") ｜ [Bilibili](https://www.bilibili.com/video/BV1Prpb67E8w/ "Bilibili")

😄 [Afdian (Sponsorship, full Autodesk Fusion (.f3z) and .step project files)](https://afdian.com/a/kuruibb "Afdian (Sponsorship)")   
🧵 [Threads](https://www.threads.net/@coreoobb "@coreoobb") @coreoobb  
🐧 QQ Group (Discussion only; if full, please join Discord): 647186542  
😈 Discord Channel: [Join](https://discord.gg/gvbcCtdQrk "Join")   

## Directory Structure

```text
CAD/                           # 3D CAD Models
├── rotate.step                # CNC machined, rotating module body
├── bot.step                   # CNC machined, stationary module mount (interfaces with rotating body)
├── top.stl                    # 3D printed, lens mount adapter (interfaces with microscope lens)
├── Mirror_3Dv2.stl            # 3D printed, mirror mount
└── prism_cover.stl            # 3D printed, prism protective cover (optional)
bbScope Materials.xlsx         # Bill of Materials (BOM)
```

## Notes

This 3D module is designed for microscope lenses with a 100mm working distance (WD100). The camera sensor/module can be chosen according to your own needs.

## Interested in Purchasing a Pre-built Unit?

Two SKUs are planned: Complete microscope unit, and Standalone 3D module.  
Currently still under consideration. Follow Bilibili, QQ Group, or Threads for the latest updates.

## Assembly Instructions

1. Tap and insert the dowel pins into the corresponding holes of `rotate.step`.
2. Secure the magnets into the corresponding holes of `rotate.step` in a uniform polarity orientation using T9000 adhesive.
3. Glue the concave lens into the center position of `rotate.step` using T9000 adhesive.
4. Glue the 25×25×25mm reflection prism directly below the concave lens using T9000 adhesive.
5. Glue the prism protective cover onto the reflection prism using T9000 adhesive (optional).
6. Press the bearing into `bot.step`. You can place a soft pad smaller than the bearing's outer diameter at the center to ensure the bearing is fully seated into the bottom.
7. Tap and insert the dowel pins into the corresponding holes of `bot.step`.
8. Secure the magnets into the corresponding holes of `bot.step` in the opposite polarity orientation (to attract with `rotate.step`) using T9000 adhesive.
9. Apply T9000 adhesive to the bottom of `top.stl`, then bond and secure `bot.step` together with the bearing onto it.
10. Glue the polarizer sheet inside `top.stl` using T9000 adhesive.
11. Screw `top.stl` along the internal threads of the microscope lens until firmly seated.
12. Magnetically attach `rotate.step` onto the bottom of the assembled `bot.step` and `top.stl` unit.
13. Snap the 37×37×1mm mirror into `Mirror_3Dv2.stl`.
14. Mount `Mirror_3Dv2.stl` to the end of `rotate.step` using two M2 screws, and use two additional M2 screws to adjust the tilt angle of the mirror.
15. Finely adjust the four M2 screws to calibrate the mirror's position, tilt angle, and yaw/rotation angle to achieve the highest possible concentricity.
