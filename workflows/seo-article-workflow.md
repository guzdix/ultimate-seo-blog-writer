# SEO Article Workflow

This workflow creates a complete SEO blog post optimized for Google Search and AI answer engines.

## Required User Inputs

Ask the user for these details if missing:

- Website URL
- Brand or business description
- Primary keyword
- Content angle
- Target word count
- CTA goal
- Target audience
- Language
- Optional personal experience, case study, or client result

## Step 1: Brand Voice Analysis

Analyze the user's website before writing.

Review:
- Homepage
- About page
- Service page
- Blog post if available

Identify:
- Tone
- Vocabulary
- Sentence rhythm
- Formality level
- CTA style
- Brand personality

Output:

```md
## Brand Voice Summary

- Tone:
- Vocabulary:
- Sentence style:
- CTA style:
- Notes:
```

## Step 2: Search Intent Research

Research the primary keyword.

Identify:
- Search intent
- Top-ranking angles
- Common subtopics
- People Also Ask questions
- Content gaps
- Featured snippet opportunities

Output:

```md
## Search Intent Analysis

[2-3 sentences]

## Competitor Pattern

[Summary]

## Content Gap Opportunity

[Summary]
```

## Step 3: Source Collection

Collect 8-15 authoritative sources.

Prioritize:
- Official sources
- Original research
- Recent data
- Trusted industry publications
- Reputable expert sources

Output:

```md
## Source Plan

| Source | Specific Insight | Article Section |
|---|---|---|
```

## Step 4: Internal Link Planning

Fetch sitemap if available:

`[website]/sitemap.xml`

Choose 4-7 relevant internal links.

Output:

```md
## Internal Links Plan

| Page URL | Anchor Text | Section | Why It Fits |
|---|---|---|---|
```

## Step 5: Outline Approval

Before writing, present the outline and wait for approval.

Output:

```md
## Proposed Article Outline

### TL;DR

### Introduction

### H2 Sections

### Conclusion

### FAQ Section

## Answer Capsule Plan

| Section | Capsule Type | Intent |
|---|---|---|
```

Do not write the full article until the user approves.

## Step 6: Full Article Writing

Write using the blog template.

Rules:
- Use primary keyword in title, introduction, and 2-3 H2s.
- Use answer capsules in about 60% of H2 sections.
- Keep reading level around 8th grade.
- Use short paragraphs.
- Add source links for factual claims.
- Add 4-7 internal links naturally.
- Avoid em dashes.
- Match brand voice.
- Integrate personal experience if provided.

## Step 7: Schema Generation

Generate:
- FAQPage schema
- BlogPosting schema if enough data is available
- BreadcrumbList schema if page structure is known

## Step 8: Final QA

Check:
- TL;DR is 50-80 words
- Primary keyword placement
- Source-backed claims
- Internal links
- Answer capsule count
- FAQ quality
- Schema validity
- No em dashes
- Clear CTA
- Paragraph length
- Reading level

## Step 9: Post-Delivery Summary

Return:

```md
## Post-Delivery Summary

- Word count:
- Reading level:
- External sources linked:
- Internal links:
- Answer capsule sections:
- Standard sections:
- FAQ schema:
- BlogPosting schema:
- CTA included:
```

Then ask:

"Want me to generate a meta title and meta description for this post?"