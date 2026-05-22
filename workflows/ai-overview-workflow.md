# AI Overview Optimization Workflow

This workflow improves content so it can be understood, extracted, and cited by AI answer engines.

Target engines:
- Google AI Overviews
- ChatGPT
- Perplexity
- Gemini
- Claude
- Bing Copilot

## Required User Inputs

Ask for:
- Primary keyword
- Target audience
- Website URL
- Article topic
- Preferred CTA
- Existing article draft if available

## Step 1: Identify AI Answer Intent

Classify what the user is trying to answer.

Intent types:
- Definition
- Comparison
- How-to
- Best option
- Local recommendation
- Cost or pricing
- Problem and solution
- Checklist
- Beginner guide

Output:

```md
## AI Answer Intent

Primary intent:
Secondary intent:
Best answer format:
```

## Step 2: Build Answer Capsules

Create concise answer capsules for key questions.

Each capsule must:
- Be 30-60 words
- Answer directly
- Stand alone
- Include the main entity
- Avoid vague pronouns
- Avoid fluff
- Avoid em dashes

Output:

```md
## Answer Capsules

### Question 1
[Capsule]

### Question 2
[Capsule]

### Question 3
[Capsule]
```

## Step 3: Entity Optimization

Identify semantic entities.

Include:
- Primary entity
- Related entities
- Location entities
- Brand entities
- Problem entities
- Solution entities
- Commercial entities
- Tool or method entities

Output:

```md
## Semantic Entity Map

Primary entity:
Supporting entities:
Related concepts:
Commercial entities:
Local entities:
```

## Step 4: Source and Trust Optimization

For AI answer engines, claims must be easy to verify.

Add:
- Authoritative sources
- Official references
- Recent statistics
- Expert sources
- Transparent limitations

Output:

```md
## Citation Plan

| Claim | Source | Placement |
|---|---|---|
```

## Step 5: Extractable Structure

Rewrite or create sections using:

- Clear H2 question headings
- Direct answer first
- Short paragraphs
- Bullets when useful
- Tables for comparisons
- FAQ for long-tail answers
- Summary blocks

Recommended structure:

```md
## What is [topic]?
[Answer capsule]

## How does [topic] work?
[Answer capsule]

## Why does [topic] matter?
[Answer capsule]

## [Topic] best practices
[Editorial section]

## Common mistakes
[Editorial section]

## FAQ
```

## Step 6: AI Overview QA

Check each important section:

- Does it answer the question in the first 1-2 sentences?
- Can the paragraph stand alone?
- Are entities clear?
- Are claims sourced?
- Is the wording simple?
- Is there no em dash?
- Is the answer useful without extra context?

## Step 7: Final Output

Return:

```md
## AI Overview Optimization Summary

- Primary AI intent:
- Answer capsules created:
- Entities added:
- Sources recommended:
- FAQ opportunities:
- Snippet opportunities:
- Risk notes:
```

## Writing Rules

Always:
- Be direct
- Use simple language
- Cite facts
- Name the topic clearly
- Use structured formatting

Never:
- Use vague introductions
- Overpromise rankings
- Fake experience
- Use em dashes
- Hide the answer deep in the section