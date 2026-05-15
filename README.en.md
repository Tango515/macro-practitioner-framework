# Macro Practitioner Framework

[简体中文](README.zh-CN.md) | English

This repository contains a practical macro investing framework and two Codex skills, one in English and one in Chinese.

The framework is based on practitioner thinking from George Soros, Ray Dalio, and Stanley Druckenmiller. It intentionally avoids academic finance models that rely on strong equilibrium assumptions. The goal is to produce an action-oriented process for macro analysis, positioning, risk control, and review.

## Core Idea

Macro investing is not about forecasting isolated data points. It is about identifying the forces pushing the world away from an old regime, understanding how policy, credit, liquidity, expectations, and positioning reinforce that move, and expressing the view where odds and risk are acceptable.

## Practitioner Lenses

1. **George Soros**
Markets are not passive mirrors of fundamentals. Prices, narratives, financing conditions, and policy responses can reshape reality. The key is to identify reflexive feedback loops.

2. **Ray Dalio**
Debt, money, credit, cash flow, and policy constraints drive macro regimes. The key is to identify the cycle and what cannot continue.

3. **Stanley Druckenmiller**
Large gains come from a few periods when the evidence lines up. The key is to use market internals and forward-looking signals, then size up only when the setup is validated.

## Six Drivers

Use these six drivers in every macro review:

1. Growth
2. Inflation
3. Credit
4. Liquidity
5. Policy constraints
6. Capital flows

## Standard Analysis Flow

1. Define the current regime in one sentence.
2. Map the six drivers.
3. Write the dominant causal chain.
4. Identify the reflexive loop.
5. Identify the unsustainable point.
6. State the market consensus and likely mispricing.
7. List catalysts that could force repricing.
8. Choose the cleanest asset expressions.
9. Define validation signals.
10. Define invalidation conditions.
11. Convert the view into action guidance.

## Repository Structure

```text
.
├── README.md
├── README.en.md
├── README.zh-CN.md
├── macro_investing_framework.md
└── skills
    ├── macro-practitioner-framework
    │   ├── SKILL.md
    │   ├── agents
    │   │   └── openai.yaml
    │   └── references
    │       └── framework.md
    └── macro-practitioner-framework_cn
        ├── SKILL.md
        ├── agents
        │   └── openai.yaml
        └── references
            └── framework_cn.md
```

## Install as Codex Skills

Copy either skill folder into your Codex skills directory:

```powershell
Copy-Item -Recurse -Force ".\skills\macro-practitioner-framework" "$env:USERPROFILE\.codex\skills\"
Copy-Item -Recurse -Force ".\skills\macro-practitioner-framework_cn" "$env:USERPROFILE\.codex\skills\"
```

Restart Codex after copying.

## Usage Prompts

English:

```text
Use the macro-practitioner-framework to analyze the current macro regime. Include the driver map, causal chain, best expressions, validation signals, invalidation conditions, and action guidance.
```

Chinese:

```text
请用宏观实干派框架分析当前宏观环境，输出驱动器地图、主导因果链、最佳资产表达、验证信号、失效条件和行动建议。
```

## Risk Note

This framework is for research and decision support. It is not financial advice. Any real positioning decision should account for portfolio constraints, liquidity, risk tolerance, and the possibility that the macro thesis is wrong.
