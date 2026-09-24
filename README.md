# 留学申请课程描述 Skill

这是一个适用于不同学校和专业的 Codex skill，用于根据可信的课程材料制作英文课程描述。仓库根目录的 `SKILL.md` 是运行所需的唯一文件；`README.md` 仅说明如何安装和使用。

## 安装

在 Codex 中输入：

```text
$skill-installer 请从 Raven49963/study-abroad-course-descriptions-skill 安装仓库根目录（--path .）的 skill，名称设为 study-abroad-course-descriptions。
```

也可以手动把本仓库的 `SKILL.md` 放入 `~/.codex/skills/study-abroad-course-descriptions/`；Windows 对应路径通常是 `C:\Users\<用户名>\.codex\skills\study-abroad-course-descriptions\`。若安装后没有出现在技能列表中，重启 Codex。

## 准备材料

- **必需：**成绩单或教务课程清单；培养方案、课程大纲或学校官方课程说明。后者须能支持拟写的课程内容，仅有课程名称时还需要补充大纲。
- **按需：**目标院校的提交要求、已有课程描述草稿、排版模板、学校官方英文名称与校徽、封面信息。

这些材料在使用 skill 时提供给 Codex 即可，不需要上传到本 GitHub 仓库。

## 使用示例

```text
使用 $study-abroad-course-descriptions，根据我提供的成绩单、培养方案和课程大纲，制作留学申请用英文课程描述。不要列成绩，保留原校学分，输出 PDF 和可编辑源文件；无法核实的课程请单独列出。
```

可在请求中指定收录课程、目标院校模板、语言和是否显示成绩。缺少关键课程内容时，skill 会先指出需要补充的材料。
