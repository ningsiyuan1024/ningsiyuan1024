# Sylan

我关注 Agent 如何完成一项任务，以及怎样判断它在哪一步出了错。这里放了两个可以沿着执行过程读的实验，也放了一张可以直接用的 AI 公司地图。

**[Twenty Agent Loops](https://github.com/ningsiyuan1024/twenty-agent-loops)** · Agent 执行机制  
同样是收到一批工具结果，有的循环继续请求模型，有的直接结束。这个实验用 Python 和 TypeScript 把这些分支跑出来，再和固定版本的上游实现对照。建议从 [pi 的五组探针](https://github.com/ningsiyuan1024/twenty-agent-loops/blob/main/reports/fidelity-pi-probe.json) 开始：其中四组观察到了差异，可以看到教学实现遗漏了什么。

**[AI-Talent](https://github.com/ningsiyuan1024/ai-talent-career-copilot)** · LangGraph 应用原型  
把多轮访谈整理成结构化画像，再并行生成职场优势、创作优势和导师匹配等材料，最后组装报告。仓库提供无需模型密钥的规则模式；[验收说明](https://github.com/ningsiyuan1024/ai-talent-career-copilot/blob/deepseek-mainline-handoff-20260419/docs/acceptance.md) 列出了每一步该交付什么。

**[AI 公司地图 ↗](https://ningsiyuan1024.github.io/ai-company-map/)** · 可直接使用的数据产品  
按城市和方向查找 AI 团队，从公司详情返回招聘与地址来源。只确认到城市的公司也可以检索，地图不会给它猜一个办公地点。[数据与核验方式](https://github.com/ningsiyuan1024/ai-company-map#数据与核验)

**[Photo2Memory](https://github.com/ningsiyuan1024/photo2memory)** · 创意 AI  
一张旅行照片，可以做成一本纸刊，也可以做成一幅记忆三联画。这个小型索引按输入和作品形式整理方法，保留原作者、案例与核验状态，方便选到合适的方法动手试。

[个人博客](https://ningsiyuan1024.github.io/)
