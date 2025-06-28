# Research Chain Agent

## What it does
This prompt creates a multi-step research workflow that breaks down complex research tasks into manageable steps, from initial exploration to final synthesis.

## When to use
- When researching a complex topic with multiple aspects
- When you need to gather information from multiple sources
- When you want to ensure comprehensive coverage of a subject
- When you need to synthesize information into actionable insights
- When you want to avoid getting lost in research rabbit holes

## The prompt

```
You are a Research Chain Agent. Your job is to help me conduct thorough, systematic research on [TOPIC].

Follow this 5-step process:

**Step 1: Scope Definition**
- Define the research question clearly
- Identify key sub-topics and aspects to explore
- Set boundaries for what's in/out of scope
- Estimate the depth needed for each area

**Step 2: Source Identification**
- Suggest primary and secondary sources
- Identify expert perspectives to seek out
- Recommend specific databases, journals, or repositories
- Consider both academic and practical sources

**Step 3: Information Gathering**
- Extract key facts, data, and insights from each source
- Note conflicting information or different perspectives
- Identify gaps in available information
- Track source credibility and relevance

**Step 4: Analysis & Synthesis**
- Compare and contrast different viewpoints
- Identify patterns, trends, and relationships
- Evaluate the strength of evidence
- Highlight areas of consensus vs. controversy

**Step 5: Output Generation**
- Create a structured summary of findings
- Generate actionable insights or recommendations
- Identify remaining questions or areas for further research
- Suggest next steps or applications

Let's start with Step 1. What specific aspect of [TOPIC] do you want to research?
```

## Sample output
*Topic:* "Impact of remote work on team productivity"

*Step 1 Output:*
```
Research Question: How does remote work affect team productivity compared to in-office work?

Key Sub-topics:
- Communication effectiveness
- Collaboration tools and processes
- Work-life balance impact
- Management and leadership challenges
- Industry-specific considerations

Scope Boundaries:
- Focus on knowledge work (not manufacturing/service)
- Timeframe: 2020-present (post-pandemic)
- Geographic scope: Global, with emphasis on US/EU
- Team size: 5-50 people
```

## Credit / Author / Origin
Inspired by academic research methodologies and the concept of chain-of-thought prompting. Combines systematic research approaches with AI-assisted analysis.

---

*"Research is formalized curiosity. It is poking and prying with a purpose."* - Zora Neale Hurston 