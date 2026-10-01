# ChatGPT Command Library v1.0

**Purpose:** A reusable command system for turning ChatGPT into a structured research, learning, documentation, and knowledge-management assistant.

---

## 01 — `/extract`

**Purpose:** Extract useful information from an image, document, screenshot, or supplied content.

**Command:**
`/extract`

**Default output:**
- Exact information
- Structured information
- Important details
- Unclear / missing information

**Useful extensions:**
- `/extract text`
- `/extract table`
- `/extract key information`
- `/extract + organize`

---

## 02 — `/store`

**Purpose:** Preserve useful ChatGPT output in Notion without unintentionally changing the original answer.

**Command:**
`/store`

**Default instruction:**
> Store the previous ChatGPT answer in Notion as an exact capture. Preserve the original wording, structure, examples, terminology, and conclusions. Do not summarize, rewrite, improve, or reinterpret it.

**Useful extensions:**
- `/store exact`
- `/store summary`
- `/store + organize`
- `/store as original`

**Key distinction:**

`/store exact` → preserve ChatGPT's answer  
`/store summary` → compress the answer  
`/store + organize` → restructure it for future retrieval

---

## 03 — `/next`

**Purpose:** Find the next logical learning or action step after completing a task.

**Command:**
`/next`

**Default instruction:**
> Based on what we have completed, identify the next logical step. Prioritize the step that gives the highest practical value and builds naturally on the current knowledge.

**Output:**
1. Next step
2. Why it matters
3. What I should do
4. Expected result
5. Optional advanced step

---

## 04 — `/related`

**Purpose:** Discover adjacent knowledge that is useful but has not yet been covered.

**Command:**
`/related`

**Default instruction:**
> Identify important related concepts, terminology, risks, practical knowledge, and next-level topics that are directly connected to this subject but have not yet been covered.

**Output:**
- Essential missing knowledge
- Useful terminology
- Common misconceptions
- Practical applications
- Advanced concepts

---

## 05 — `/ultimate`

**Purpose:** Push a topic from basic understanding toward a comprehensive knowledge framework.

**Command:**
`/ultimate`

**Default instruction:**
> Take this topic to an advanced practical level. Identify the core concepts, terminology, relationships, hidden assumptions, failure modes, practical applications, and higher-level knowledge I should understand.

**Preferred structure:**
`Core → Terminology → Mechanism → Comparison → Failure modes → Application → Advanced concepts`

---

## 06 — `/poster`

**Purpose:** Convert knowledge into a visual educational poster.

**Command:**
`/poster`

**Default instruction:**
> Turn this knowledge into a clear technical educational poster. Organize the information visually from fundamental concepts to practical application. Prioritize hierarchy, concise terminology, relationships, and memorable explanations.

**Default sections:**
- Title
- Core concept
- Key terminology
- How it works
- Important comparisons
- Practical rules
- Common mistakes
- Quick reference

---

## 07 — `/compare`

**Purpose:** Compare multiple products, technologies, concepts, or approaches systematically.

**Command:**
`/compare`

**Default instruction:**
> Compare the items using the criteria that materially affect the decision. Separate objective specifications, practical differences, trade-offs, limitations, and use cases. Do not hide important differences behind a single overall rating.

**Preferred structure:**

| Criterion | A | B | C |
|---|---|---|---|
| Core function | | | |
| Performance | | | |
| Limitations | | | |
| Cost/value | | | |
| Practical use | | | |
| Best-fit scenario | | | |

---

# Command Chaining

The real value of the library is **combining commands**.

### Research → Knowledge

`/related → /ultimate`

Find what is missing, then deepen the topic.

### ChatGPT → Notion

`/store exact`

Preserve the answer first.

Then:

`/store + organize`

Create a reusable knowledge structure.

### Learning → Action

`/ultimate → /next`

Understand the subject, then determine what to do next.

### Knowledge → Visual

`/ultimate → /poster`

Build the knowledge framework first, then convert it into a visual reference.

### Product research

`/extract → /compare → /related → /next`

Extract specifications → compare → discover overlooked factors → decide what to investigate next.

---

# v1.0 Command Principles

### 1. Capture before transformation

When an answer may be valuable later:

`/store exact`

before:

`/store + organize`

This prevents useful original information from being lost during summarization.

### 2. Separate knowledge from action

Use:

`/ultimate` = **What should I understand?**

`/next` = **What should I do next?**

### 3. Separate discovery from synthesis

Use:

`/related` = **What am I missing?**

`/ultimate` = **How does the whole system fit together?**

### 4. Use visual output last

Prefer:

`Understand → Structure → Visualize`

rather than immediately asking for a poster.

---

# Recommended Core Set

If only **five commands** are retained for daily use:

| Command | Main function |
|---|---|
| `/extract` | Get information out |
| `/related` | Find what is missing |
| `/ultimate` | Build deep understanding |
| `/next` | Determine the next action |
| `/store exact` | Preserve valuable ChatGPT output |

**Core workflow:**

`EXTRACT → RELATED → ULTIMATE → NEXT → STORE`

This is the foundation of ChatGPT Command Library v1.0.
