# Topical Cluster Workflow

This workflow creates a topical authority plan around a primary SEO topic.

It is used to help a website rank for a wider topic, not just one keyword.

## Required User Inputs

Ask for:
- Website URL
- Main topic
- Business type
- Target location
- Target audience
- Main product or service
- Existing important pages
- Preferred CTA

## Step 1: Define the Pillar Topic

Identify the broad topic the website should own.

Output:

```md
## Pillar Topic

Main topic:
Primary keyword:
Audience:
Business goal:
Search intent:
```

## Step 2: Identify Topic Entities

Extract entities related to the main topic.

Include:
- Main entity
- Supporting entities
- Location entities
- Product or service entities
- Problem entities
- Benefit entities
- Comparison entities
- FAQ entities

Output:

```md
## Entity Map

| Entity | Type | Why It Matters |
|---|---|---|
```

## Step 3: Build Content Cluster

Create a content map with:

1. Pillar Page  
Broad guide or commercial hub.

2. Supporting Blog Posts  
Specific questions and subtopics.

3. Commercial Pages  
Service, product, or landing pages.

4. FAQ / Answer Pages  
Short long-tail query pages.

5. Comparison Pages  
Useful for commercial investigation intent.

Output:

```md
## Content Cluster Plan

### Pillar Page

| Page Type | Suggested Title | Target Keyword | Intent | CTA |
|---|---|---|---|---|

### Supporting Blog Posts

| Suggested Title | Target Keyword | Intent | Internal Link Target |
|---|---|---|---|

### Commercial Pages

| Suggested Page | Target Keyword | CTA |
|---|---|---|

### FAQ Pages

| Question | Intent | Link Target |
|---|---|---|

### Comparison Pages

| Suggested Title | Compared Topics | CTA |
|---|---|---|
```

## Step 4: Internal Linking Architecture

Plan how pages should link to each other.

Rules:
- Pillar page links to all supporting posts.
- Supporting posts link back to the pillar page.
- Supporting posts link to related commercial pages.
- Commercial pages link to relevant guides.
- FAQ pages link to deeper articles.
- Avoid orphan pages.

Output:

```md
## Internal Linking Strategy

### Pillar to Cluster Links

### Cluster to Pillar Links

### Blog to Commercial Links

### FAQ to Supporting Content Links
```

## Step 5: Publishing Priority

Rank pages by priority.

Consider:
- Business value
- Keyword intent
- Ranking difficulty
- Content gap
- Conversion potential
- Existing authority

Output:

```md
## Publishing Priority

| Priority | Page Title | Reason |
|---|---|---|
```

## Step 6: Content Briefs

For each high-priority page, create a mini brief.

Output:

```md
## Content Brief

### Title

Primary keyword:
Search intent:
Target reader:
Recommended word count:
Required sections:
Internal links:
CTA:
Schema:
```

## Step 7: Topical Authority QA

Check:
- Does the cluster cover the full user journey?
- Does each page have a unique intent?
- Are topics overlapping too much?
- Are commercial pages supported by educational content?
- Are internal links clear?
- Are there enough FAQ opportunities?
- Is the pillar page strong enough?

## Final Output

Return:

```md
## Topical Cluster Summary

- Pillar topic:
- Total supporting posts:
- Total commercial pages:
- Total FAQ opportunities:
- Total comparison pages:
- First 5 pages to publish:
- Main CTA strategy:
```