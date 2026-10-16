# product-to-jimeng-comic

根据产品资料生成即梦漫剧制作素材包。

面向即梦的跨品类商品漫剧制作 skill，适用于电视、空调及其他商品。

## 能做什么

- 产品、重点卖点明确：直接写脚本；尚未明确：先提供选题。
- 脚本确认后，生成一张多格分镜图和完整即梦视频提示词。
- 默认10秒、9:16，分镜数量与画风按剧情调整。
- 明确配音、字幕、音乐与音效要求，核对产品外观及卖点依据。

交付的是制作素材包，不会自动登录即梦或生成最终视频。

## 安装到 Codex

将本仓库链接发给 Codex，并说：

> 请使用 skill-installer，从这个 GitHub 仓库的 skills/product-to-jimeng-comic 目录安装 skill。

也可以下载仓库，把完整的 product-to-jimeng-comic 文件夹放入个人 Codex 技能目录。不要只复制 SKILL.md，references 和 agents 目录也需要保留。

## 使用

安装后，在下一轮对话输入：

> 使用 $product-to-jimeng-comic，为这款电视制作10秒漫剧。重点突出低反光，实机图和产品资料见附件。

未选好卖点时：

> 使用 $product-to-jimeng-comic，根据附件里的电饭煲资料，先给我几个漫剧选题。

准备实机图和可靠的产品资料。按顺序确认选题（如需）和脚本；拿到素材后，将实机图、分镜图与提示词用于即梦。

## 环境要求

需要能够加载 skill 的 Codex 环境。生成分镜图还需要可用的图像生成能力；文字 skill 本身不提供模型、账号或额度。即梦成片由使用者自行生成。

## 文件

- skills/product-to-jimeng-comic/SKILL.md：流程规则。
- skills/product-to-jimeng-comic/references/delivery-contract.md：交付模板。
- skills/product-to-jimeng-comic/agents/openai.yaml：技能显示信息。

本仓库分享的是通用流程与模板，不包含产品原图、内部产品资料或用户成片。
