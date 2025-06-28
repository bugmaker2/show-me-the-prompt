# Tree of Thought Prompt

## What it does
This prompt implements the Tree of Thoughts (ToT) framework, which helps break down complex problems into a branching structure of possible solutions and their implications.

## When to use
- When facing complex, multi-step problems
- When you need to explore multiple solution paths
- When making important decisions with many variables
- When you want to think systematically about trade-offs
- When you need to avoid getting stuck on one approach

## The prompt

```
I want to solve this problem using the Tree of Thoughts method: [DESCRIBE YOUR PROBLEM]

Please help me build a decision tree where:

1. **Root**: Start with the main problem/question
2. **Branches**: Each node represents a possible approach, decision, or step
3. **Leaves**: End points that represent potential solutions or outcomes
4. **Evaluation**: For each path, consider pros, cons, and likelihood of success

For each branch, ask:
- What are the immediate next steps?
- What could go wrong?
- What are the alternatives?
- How likely is this to succeed?
- What resources would this require?

Let's start by identifying the main decision points and then explore each branch systematically.
```

## Sample output
*Problem:* "Should I start a side business while keeping my full-time job?"

*AI builds tree:*
```
Root: Start side business while keeping job?
├── Branch 1: What type of business?
│   ├── Consulting (low startup cost, high hourly rate)
│   ├── E-commerce (higher risk, potential for scale)
│   └── Content creation (passive income potential)
├── Branch 2: Time management approach
│   ├── Dedicated evening hours
│   ├── Weekend focus
│   └── Flexible scheduling
└── Branch 3: Risk assessment
    ├── Financial risk (minimal if keeping job)
    ├── Time risk (burnout potential)
    └── Career risk (conflict of interest)
```

## Credit / Author / Origin
Based on the Tree of Thoughts framework developed by researchers at Google and Princeton. The method was introduced in the paper "Tree of Thoughts: Deliberate Problem Solving with Large Language Models" (2023).

---

*"The best way to predict the future is to invent it."* - Alan Kay 