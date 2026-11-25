# OC2 自适应视角 / OC2 Adaptive Camera

在《胡闹厨房 2》的原版和自制关卡中，让镜头优先跟随本机正在操作的厨师。可在游戏进行时调整取景范围、跟随速度、边缘防拉伸和传送门平移曲线，再保存到本关或作为通用设置。本机两人及以上时保持原版镜头。

## 安装与使用

1. 在已安装 BepInEx 5 的 Mono 版游戏中，下载 [最新 Release](https://github.com/CH3NGY2/Overcooked-2-AdaptiveCamera/releases/latest) 的 ZIP。解压，将 `OC2AdaptiveCamera.dll` 放到 `BepInEx/plugins/` 后重启游戏。
2. 在 [MOD 设置](https://github.com/CH3NGYZ/Overcooked-2-ModSettings/releases) 开启「启用视角自定义」，以本机单人进入关卡，再选「进入视角编辑模式」。可以边操作厨师边预览；保存前不改写现有配置。
3. 「保存到本关」只改当前关卡；「保存为通用设置」只影响没有单关配置的关卡。没有保存过配置时，退出预览后使用原版镜头。

简繁中文按钮每行四字需要 MOD 设置支持独立按钮文案。公开版 1.2.1 仍可提供编辑入口，只是按钮显示单行。

## English

Follow the chef you control in official and custom kitchens. Preview framing, camera speed, edge distortion reduction, and portal motion while playing. Save settings for the current level or use them as the default. With two or more local players, the original camera stays in use.

Install BepInEx 5 for the Mono game, extract `OC2AdaptiveCamera.dll` from the [latest release](https://github.com/CH3NGY2/Overcooked-2-AdaptiveCamera/releases/latest) into `BepInEx/plugins/`, and restart. Enable camera customization in [MOD Settings](https://github.com/CH3NGYZ/Overcooked-2-ModSettings/releases), then open the camera editor while inside a level with one local player. A level-specific profile takes priority over the default. MOD Settings 1.2.1 supports the editor action; a provider that supports separate captions is needed for the two-line Chinese button.
