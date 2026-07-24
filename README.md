# easycodeSkill

可复用的 Codex Skills 集合。每个 Skill 均为独立目录，可按需安装和组合使用。

当前在 `skills/resume/` 下收录一套通用技术简历工作流，不包含任何特定候选人的简历、照片、联系方式或项目经历。使用时请提供自己的旧简历、工作材料和目标 JD。

## Skills

- `job-description-analyzer`：分析 JD、岗位匹配度和能力缺口
- `resume-builder`：根据已有材料生成中文简历
- `resume-tailoring`：针对目标岗位定制简历
- `tech-resume-optimizer`：强化技术深度、系统规模和业务影响
- `resume-bullet-writer`：将工作描述改写为结果导向的简历要点
- `resume-section-builder`：构建个人概述、技能、工作和项目模块
- `resume-ats-optimizer`：检查 ATS 兼容性和关键词覆盖
- `resume-formatter`：生成清晰、易读的简历版式
- `interview-prep-generator`：根据简历生成 STAR 故事和面试问题

## 安装

将需要的 Skill 目录复制到 Codex Skills 目录：

```bash
cp -R skills/resume/<skill-name> ~/.codex/skills/
```

也可以一次安装全部：

```bash
cp -R skills/resume/* ~/.codex/skills/
```

重新打开 Codex 任务后即可使用，例如：

```text
Use $resume-builder to create a resume from my existing resume and this JD.
```
