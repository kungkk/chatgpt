## ChatGPT Command Library v1.1

Yes. The logical v1.1 is to evolve the library from a **list of commands** into a **command language**—so you can give shorter prompts while getting predictable outputs.

## 1. Universal command syntax

Use:

`/COMMAND [subject] [goal] [constraints] [output]`

For example:

`/compare wireless mic batteries runtime safety Malaysia table`

Instead of writing a long instruction every time.

---

## 2. Standard command grammar

| Component | Meaning | Example |
|---|---|---|
| `/command` | What ChatGPT should do | `/compare` |
| `subject` | What it should work on | `rechargeable batteries` |
| `goal` | What you want to achieve | `choose for wireless mics` |
| `constraints` | Important boundaries | `Malaysia, continuous charging` |
| `output` | Desired format | `table + recommendation factors` |

So:

`/compare rechargeable batteries choose for wireless mics Malaysia continuous charging table`

becomes a complete instruction.

---

## 3. Upgrade the seven commands

### `/extract`

`/extract [source] [what] [format]`

Example:

`/extract image text table`

---

### `/compare`

`/compare [items] [criteria] [context] [format]`

Example:

`/compare AA rechargeable batteries runtime safety Malaysia table`

---

### `/related`

`/related [topic] [depth]`

Example:

`/related wireless microphone batteries practical advanced`

---

### `/ultimate`

`/ultimate [topic] [focus]`

Example:

`/ultimate battery charging safety focus on wireless microphones`

---

### `/next`

`/next [current state] [goal]`

Example:

`/next understand rechargeable batteries → wireless mic maintenance`

---

### `/poster`

`/poster [topic] [audience] [style] [format]`

Example:

`/poster rechargeable batteries technician technical A4`

---

### `/store`

`/store [mode] [destination]`

Example:

`/store exact Notion`

---

# 4. Introduce command modifiers

This is the biggest v1.1 improvement.

### `/exact`

Preserve information without rewriting.

`/store exact`

### `/brief`

Keep only essential information.

`/ultimate brief`

### `/deep`

Increase analytical depth.

`/compare deep`

### `/practical`

Focus on real-world implementation.

`/ultimate practical`

### `/technical`

Use technical terminology and mechanisms.

`/poster technical`

### `/beginner`

Explain without assuming prior knowledge.

`/ultimate beginner`

### `/business`

Use workplace-safe language and practical business context.

`/compare business`

### `/Malaysia`

Localize prices, availability, standards, terminology, and practical considerations where relevant.

`/compare Malaysia`

---

# 5. Command combinations

You can now build commands almost like Lego.

### Learning

`/ultimate + /beginner`

→ Deep subject, but explained clearly.

### Technical research

`/ultimate + /technical + /practical`

→ Mechanism + technical terminology + real-world application.

### Decision research

`/compare + /deep + /Malaysia`

→ Detailed comparison with Malaysian context.

### Knowledge discovery

`/related + /deep`

→ Find concepts you probably haven't considered.

### Knowledge capture

`/store + /exact`

→ Archive the answer without modification.

### Visual learning

`/ultimate → /poster`

→ Understand first, visualize second.

---

# 6. Add a `/check` command

This is the major command missing from v1.0.

### `/check`

**Purpose:** Test whether an answer, assumption, plan, or conclusion is actually sound.

Syntax:

`/check [subject] [what to verify]`

Example:

`/check battery advice continuous charging`

Output:

- Confirmed
- Uncertain
- Incorrect
- Missing context
- Evidence needed
- Corrected version

This prevents your command system from becoming an **information collection system without an error-control system**.

---

# 7. Add `/distill`

Another useful v1.1 command:

### `/distill`

Turn a large answer into a compact reusable mental model.

Example:

`/distill rechargeable battery charging`

Output:

**Core idea → 5 rules → key terminology → common mistake → practical rule**

This is different from `/summary`.

`/summary` = shorter version  
`/distill` = **more usable version**

---

# 8. Add `/apply`

Move knowledge into a real situation.

### `/apply`

Syntax:

`/apply [knowledge] [situation]`

Example:

`/apply battery knowledge church wireless microphones`

Output:

1. Situation
2. Relevant principles
3. Recommended workflow
4. Risks
5. Checklist

This is particularly useful for your **church facilities/equipment work**.

---

# 9. v1.1 command architecture

```
                    CHATGPT COMMAND LIBRARY
                              │
             ┌────────────────┼────────────────┐
             │                │                │
         DISCOVER          UNDERSTAND        VERIFY
             │                │                │
         /extract          /ultimate          /check
         /related          /distill
             │                │
             └──────────┬─────┘
                        │
                      APPLY
                        │
                      /apply
                        │
                 ┌──────┴──────┐
                 │             │
              COMPARE        CREATE
                 │             │
             /compare        /poster
                 │
                 │
              ACTION
                 │
               /next
                 │
              CAPTURE
                 │
            /store exact
```

## v1.1 core set

I would therefore expand your daily core from **5 → 10 commands**:

| Command | Function |
|---|---|
| `/extract` | Get information |
| `/related` | Find missing knowledge |
| `/ultimate` | Understand deeply |
| `/distill` | Build a usable mental model |
| `/check` | Verify correctness |
| `/compare` | Analyze differences |
| `/apply` | Apply knowledge |
| `/next` | Determine next action |
| `/poster` | Visualize knowledge |
| `/store exact` | Preserve the original |

### The new core workflow

**`EXTRACT → RELATED → ULTIMATE → CHECK → DISTILL → APPLY → NEXT → STORE`**

That is a more mature system than simply collecting prompts. It gives you a **repeatable knowledge-processing pipeline**.