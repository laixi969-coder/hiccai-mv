# 来源与许可范围

## MV 创作基础

本仓库在本地提供的 MV Prompt Director 交付包上，按用户要求完成时尚先锋方向、镜头衔接、连续性与人物造型扩展，并以 hiccai-MV 作为当前展示名称。原交付包的商业使用授权条款原文保留在 [LICENSE.md](LICENSE.md)，其中的原产品名称用于标明来源，不是当前调用标识。

本次改名和功能扩展不构成将原交付包重新许可为 MIT 的声明。

## 人物结构与妆容方法

- 项目：[南鸢·人像角色设定师](https://github.com/nuyoah-ai-works/nuyoah-portrait-character-designer)。
- 作者：南鸢 nuyoah。
- 参考版本：v0.2.1，提交 `99b9a2c90e5b09507c6a61b5c27b9e2740ddb63d`。
- 上游许可：MIT，完整声明保留于 [licenses/nuyoah-MIT.txt](licenses/nuyoah-MIT.txt)。
- 主要参考：`references/decision-rules.md`、`references/structure-and-compatibility.md`、`references/makeup-adaptation.md`、`references/check-contract.md`。

本仓库将其气质到具体视觉选择、结构/妆容/光影分离、固定项与自由项、局部修改及多角色区别等方法，适配进 [人物与时尚造型](references/character-fashion.md)。其中源自上游的内容继续保留上游 MIT 权利及声明，不受原交付包条款收窄；MV 表演、转场、时间状态与全片先锋表达为本次整合扩展。

未引入上游生图工具调用、人物评分脚本、案例署名或强制逐人独立输出格式，无需安装上游 Skill。未将上游程序回归结果作为本仓库的验证结果，也未据此宣称视频身份或生成质量已验证。

## 镜头语言与导演方法

- 参考项目：[Film Cinematography Master](https://github.com/mrg123/film-cinematography-master)，仓库维护者 mrg123。
- 参考提交：`77c08e06e646d003455e2c699e72aebb2328c402`。
- 参考文件：[SKILL.md](https://github.com/mrg123/film-cinematography-master/blob/77c08e06e646d003455e2c699e72aebb2328c402/SKILL.md)。
- 上游 [README](https://github.com/mrg123/film-cinematography-master/blob/77c08e06e646d003455e2c699e72aebb2328c402/README.md) 的许可栏标为 MIT；该提交仅含 README.md 和 SKILL.md，没有独立许可全文或版权年份声明。本仓库保留这一来源事实，不代上游编造许可全文或版权信息，也不将其许可声明扩大到本仓库其他内容。

[镜头语言与场面调度](references/cinematography.md) 吸收其运镜分类、情绪候选、观看动机和导演风格入口，以本项目的 MV 任务重新编写操作规则。新增观看位置、人物/空间调度、时间可行性与模板压缩要求；区分推轨和变焦、转向和位移、焦点转移和持续跟焦。保留运动接静止、持续观看和形式实验的选择空间，不继承情绪与技法一一对应的绝对结论。

未逐段复制上游百科、电影场景分析或导演名言，也不将其示例视为已核实的电影史事实。导演方向表是创作候选，不是对导演全部作品的事实概括。

技术核对参考：[Adobe 滑动变焦说明](https://www.adobe.com/creativecloud/video/production/cinematography/camera-shots-and-angles/dolly-zoom-shot.html)、[RED 焦点转移说明](https://docs.red.com/955-0155_v7.0/WEAPONEPICWOperationGuide/en-us/Content/5_Advanced_Menus/6_Focus/Rack_Focus.htm)、[Autodesk 机位与变焦说明](https://download.autodesk.com/us/maya/2010help/files/Camera_set_up_Camera_aim_.htm)。这些资料帮助核对术语，不构成任何视频生成平台的能力或效果保证。
