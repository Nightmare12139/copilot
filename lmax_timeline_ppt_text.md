# lmax_timeline_ppt_text.md

Slide title:
LMAX & Low-Latency Ecosystem — 发展时间线

Slide layout:
- Title at top: "LMAX & Low-Latency Ecosystem — 发展时间线 (Timeline)"
- Horizontal timeline centered (use lmax_timeline.svg provided)
- Under each node (year) a short pill with 1-line description

Nodes (text for each pill, editable):

1. 2000s
   - "Concepts: in-memory, event-driven ideas"

2. 2010–2011
   - "LMAX design & whitepaper"

3. 2011
   - "Disruptor open-sourced"

4. 2012–2014
   - "Language ports & tooling growth"

5. 2013–2015
   - "Aeron / SBE / Chronicle appear"

6. 2014–2017
   - "Multi-Disruptor / sharding"

7. 2015–2019
   - "Production adoption & cross-domain use"

8. 2016–2020
   - "Academic evaluation & critique"

9. 2019–2024
   - "Cloud-native & HW acceleration"

10. 2024+
    - "Principles mainstreamed (mechanical sympathy)"

Footer note:
"Note: 节点为概览性时间点；具体年份在不同项目/公司中有差异。请在演讲中口头补充每项要点。"

Speaker notes (short script, ~40s):
"这张时间线展示了 LMAX 与低延迟生态的演进。从 2010–2011 年 LMAX 团队提出 Disruptor，到 2011 年开源，再到随后几年出现的配套组件（Aeron, SBE, Chronicle），整个生态逐步成熟。为了兼顾多核，工程上发展出多 Disruptor / 分片策略；为了解决持久化和恢复，工业界引入了顺序日志和 mmap 类方案。近几年，云原生与新硬件（NVMe, RDMA, PMEM）推动了新的适配与优化。总体上，LMAX 的核心贡献演变为一套设计原则：顺序处理、内存优先、机械同感，而不是单一实现。"
