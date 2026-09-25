# autoPRD-skill

「一句话需求 → 标准 PRD」

核心设计：不让 AI 直接生成文档，而是把 PM 的需求澄清纪律固化进 skill 工作流——先反问澄清（一轮、3~4 个高杠杆问题），再输出含用户故事、流程图、验收标准、数据埋点的标准 PRD；编不出来的事实一律标注【假设】并收进开放问题清单。

## 目录结构

```
autoPRD-skill/
├── .agents/skills/req-to-prd/
│   ├── SKILL.md                    # skill 定义：触发条件 + 四步工作流
│   └── assets/prd-template.md      # PRD 九节标准模板
├── PRD/                            # skill 运行产出的 PRD 文档
│   ├── PRD-fangke-yaoqing-v0.1.md      # 实测案例一：物业小程序访客邀请
│   └── PRD-ai-jiedai-jiqiren-v0.1.md   # 实测案例二：售楼处 AI 数字人接待
└── README.md
```

## 使用方式

在本文件夹作为工作目录打开 ZCode，skill `req-to-prd` 会自动触发；也可以直接说"帮我写个 PRD：xxx"。

## 规划

- [x] 实测案例：物业小程序访客邀请、售楼处 AI 数字人接待
- [ ] 物业费催缴（极端简短需求用例）
- [ ] 迭代记录（测试中发现的问题与 SKILL.md 修改过程）
- [ ] 作品集 PDF（设计文档 + 演示截图 + 迭代记录 + 产品化反思）
