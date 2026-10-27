# 小红书育儿博主知识库（baby）

从小红书热门育儿博主的公开笔记整理而来：视频文字稿（ASR 自动转写，可能有错字）+ 每条笔记前 20 条热门评论 + 观点/痛点分析。

最后更新：2026-10-27

## 博主

| 博主 | 主页 | 已收录笔记 | 已转写文字稿 | 已抓评论笔记 |
|---|---|---|---|---|
| 蔡优格吖~ | https://xhslink.cn/o/6pAqf7eGYMg | 171 | 171 | 171 |
| Richie老师 | https://www.xiaohongshu.com/user/profile/62e240c7000000001f004c1f | 400 | 400 | 400 |
| 魏爸育儿计划 | https://www.xiaohongshu.com/user/profile/5efc3d9f0000000001006a66 | 600（视频 555） | 555 | 151 |

说明：Richie老师 仅收录最新 400 条、魏爸育儿计划 仅收录最新 600 条；魏爸的转写和评论仍在进行中，后续会更新。

## 目录结构

每个博主一个文件夹（caiyouge / richie / weiba）：

- `raw/transcripts/`：每条视频的原始转写文本 `NNN_标题.txt`
- `raw/comments/`：每条笔记的评论原始数据（JSON，前 20 条热评）
- `raw/meta/`：笔记元数据（标题、点赞、发布日期、简介等）
- `raw/notes_list/`：笔记列表（序号|标题|点赞|笔记ID|xsec_token…）
- `notes/`：整理后的单条笔记 Markdown（信息、简介、文字稿、热评）
- `<博主>_all.md`：全部笔记合集；`<博主>_index.csv`：索引表
- `analysis/`：育儿观点与评论痛点分析（如有）
