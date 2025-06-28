# Chained Prompt Blocks

## What it does
This method breaks complex tasks into smaller, focused prompt blocks that build upon each other. Each block has a specific purpose and feeds into the next, creating a more reliable and transparent workflow.

## When to use
- When dealing with complex, multi-step tasks
- When you want to verify intermediate results
- When you need to maintain context across multiple interactions
- When you want to debug or improve specific parts of a process
- When working with tasks that have clear sequential dependencies

## The prompt

```
I want to use the Chained Prompt Blocks method for this task: [DESCRIBE YOUR TASK]

Here's how we'll break it down:

**Block 1: Task Analysis**
- Break down the main task into 3-5 sequential steps
- Identify the output format needed for each step
- Determine what information needs to be passed between blocks
- Set success criteria for each block

**Block 2: Execution**
- Work through each block one at a time
- After each block, summarize the output and confirm it meets the criteria
- If a block fails, we can iterate on just that block
- Pass relevant information to the next block

**Block 3: Integration**
- Combine outputs from all blocks
- Ensure consistency across the final result
- Validate that the complete task has been accomplished

Let's start with Block 1. What are the main components of your task?
```

## Sample output
*Task:* "Create a comprehensive business plan for a coffee shop"

*Block 1 Analysis:*
```
Step 1: Market Research
- Output: Market size, competition analysis, target customer profile
- Success criteria: 3-5 key insights with supporting data

Step 2: Financial Planning
- Output: Startup costs, revenue projections, break-even analysis
- Success criteria: Detailed spreadsheet with 3-year projections

Step 3: Operations Plan
- Output: Daily operations, staffing, supply chain
- Success criteria: Clear processes for key operational areas

Step 4: Marketing Strategy
- Output: Brand positioning, marketing channels, customer acquisition
- Success criteria: Specific tactics with budget allocations

Step 5: Executive Summary
- Output: 2-page summary of key findings and recommendations
- Success criteria: Clear, compelling narrative for stakeholders
```

## Credit / Author / Origin
Based on the concept of modular programming and the principle of separation of concerns. This approach applies software engineering principles to prompt design.

---

*"Make it work, make it right, make it fast."* - Kent Beck 