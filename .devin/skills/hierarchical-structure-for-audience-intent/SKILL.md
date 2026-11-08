---
name: hierarchical-structure-for-audience-intent
description: "Guides condensing large amounts of content for a human reader by first finding each audience's intent, then building a fractal summary (one key idea, then the next most important ideas, then details) and reviewing it several times with fresh eyes, for any report, readout, post or message that distils a lot of material, including text the user will send to someone else."
---

# Hierarchical structure for audience intent

The purpose of this skill is to give guidance on the most effective way to condense and convey large amounts of content for a human consumer. It has two parts: **hierarchical summaries** and **audience intent**. Do audience intent first, because it decides what the hierarchy is for.

## Part 1: Hierarchical summaries

Humans work most effectively by oversimplifying and then diving into the details iteratively, like a fractal. A fractal can hold effectively infinite content, which makes this approach scalable while staying tractable enough to be practical.

Think of how a human learns about the solar system. First you assume perfectly spherical planets. Later you learn how each planet is shaped differently, that Earth isn't even spherical but wider along the equator, how the moon affects its tides, and so on. All these details are like leaves. They only make sense once the tree trunk is there, then the branches, then the twigs, then the leaves. There is a hierarchy to knowledge.

The way to get to that hierarchy is to **ruthlessly prioritise and prune**.

- **If you could only say one key idea to convey the message, what would it be?** That is the trunk. Write it first.
- **Pruning isn't about text length.** It's about cutting the details and the ideas so you can be minimally wrong. A short text that says the wrong thing first is badly pruned. A long text with the right trunk and branches can be well pruned. A request for something "comprehensive" still gets a trunk; the depth lives in the lower levels.
- **Every detail can be zoomed into to reveal more detail, but each zoom level is not just a mass of leaves.** It is the next most important key ideas. Every level of the tree must itself be a ruthlessly pruned summary of what sits below it.

A lot of work goes into structuring hierarchical summaries. **Do not expect to one-shot it.** You will almost always need to review it a few times to get it right, because some information about the clarity of the structure can't be seen until it's written down.

## Part 2: Audience intent

Information rarely lives in a vacuum. It is almost always paired with a particular intent. Before you structure anything, identify the context of the task and derive the intent from it.

- **Guess several readings of intent.** Just as the summary needs several passes, you will likely need to guess at several possible readings of intent. Match each one against the data points available to check whether that reading is accurate, then use the validated reading to decide what information needs to be conveyed.
- **Always keep the target audience in mind.** An exec readout of a completed task is unlikely to need any lines of actual code.
- **There are often multiple audiences with different intents.** This applies when the target audience is the user, and also when the user asks you to craft text for someone else. In that case there are at least two audiences. The user's intent might be to understand the content properly, while the final recipient might only want a particular slice of it.

## How to apply it

### 1. Intent (before writing anything)

- **Context.** Who asked, what they asked, what came before (earlier messages, corrections), where the text goes next, and **why this communication exists at all**: what is the relationship between the sender and each reader, and what should each reader do or decide after reading?
- **Readings.** List 2 to 4 candidate readings that differ in *purpose*, not just in format (e.g. "warn them" vs "impress them" vs "get a decision"). For each, name the evidence for and against. Pick the reading that fits the data.
- **Audiences.** Name each audience, what they already know, where they stand (insider or outsider, owner or observer), and the slice they need. Serve each audience in something they will actually keep: if the user needs to understand the material, give them that layer in the deliverable (clearly marked if it shouldn't be forwarded), not only in a passing chat message.

### 2. Know the whole before you prune

You can only prune what you have seen. Read the full material, or have all of it read, before choosing the trunk. Pruning from someone else's summary inherits their pruning and their mistakes. If you can only work from secondary sources, say so where the reader will see it.

### 3. Trunk

- Write 2 to 3 **genuinely different** candidate trunks (different claims, not rewordings of one claim). Pick the one that would leave this audience least wrong if it were the only thing they read.
- The trunk is **one idea**. If it needs "and... then... but" to hold together, it is several ideas: pick the most important and move the rest into branches. Test it: could the audience repeat it from memory after one read? Reasons, numbers and qualifiers chained on with "so", "because" or dashes belong in the first branches, not the trunk.
- If you can't write it, you don't understand the material yet. Go back to the content, not to the formatting.
- When the material explains why something happened, the trunk is the deepest cause the evidence supports, not the first plausible one or the symptoms. Keep asking "why" until the next answer isn't supported, or until it's beyond anything the reader can change.

### 4. Branches and zoom levels

- Branches are the next most important ideas (usually about 3; more than 4 is a sign that siblings should be merged), each a claim that supports or qualifies the trunk. A branch that only restates the trunk is a wasted level. Order them by importance to the audience's intent, not by source, by agent or by chronology.
- Under each branch, add only what is needed to make it believable and usable: the next sub-ideas, then evidence. Raw leaves (quotes, logs, line numbers, code) go at the deepest level or in an appendix, attached to the idea they support.
- **Find the relationships before you write any branches; don't list things side by side.** Do this pruning yourself before sending, so the reader doesn't have to push you into it. Check each draft:
  - **Dependent items are stages of one parent, not siblings.** If B can only happen after A (build a platform → accredit it → deliver it), the branch is the one parent ("get it into prod") and A, B, C are its stages.
  - **Keep *what* separate from *how*.** A goal (what someone is trying to achieve) is not their working pattern, form factor or tool usage (how they go about it). "Long sessions → hand off tickets → maintain the factory" is the shape of the work, not a change of goal. Don't present one as the other.
  - **Find the real thing.** When asked for someone's goal, give the concrete outcome they're working toward (e.g. the system they're building), not the category of activity or a meta-objective.
- Orienting context (a timeline, a who's who, a glossary) is scaffolding, not a branch. Keep it short and put it where it helps the reader follow, usually just after the top level or in a reference section.
- Prune: for each item ask "if I cut this, is the reader more wrong about anything that matters to their intent?" If not, cut it or push it down. Ask the same about what's missing.

### 5. Stay true while simplifying

Oversimplifying is allowed; inventing is not. The pressure to make a clean story can merge separate events, turn a correlation into a cause, or state a fact that is true from your position but false from the reader's (e.g. "fixed" when it is fixed only in your copy). After drafting, check every trunk and branch claim against the source and from each reader's position: next to each top-level claim, write down who it is true for. "Fixed", "ours", "safe", "done" and "no one" are the words that most often flip. An error at the top level is the most costly kind, because it is the part everyone reads. When a check changes a fact, don't just fix the wording: ask whether the trunk or the order of branches should change too. A fact that flips from the reader's position is often the reader's headline.

### 6. Review passes, with fresh eyes

You wrote it, so you can't read it cold. **Always get at least one reader that lacks your context**: a subagent or child session given only a frozen copy of the draft (no source, no task), told who the target audience is and where they stand relative to the writer. Ask it to restate the main message in one sentence, say what it would do next as that audience, list anything confusing, contradictory or unbelievable, and name anything that is true for the writer but might not be true for that reader. Compare that against your intent and fix what it found. If its one-sentence restatement is shorter than your trunk and still right, it is probably the better trunk. Re-reading your own draft is not a substitute; only skip the fresh reader if you have no way to start one, and say so. Then, yourself:

- Read only the top level. Does it convey the message on its own, and is it still true if the reader stops there?
- Read the branch titles alone. Are they the next most important ideas, or a list of topics or sources?
- Read it as each audience. Does every part serve that audience's intent? Is anything there just because it was available?

Fix the structure and reread. **A review pass that changes nothing is suspect**: look again. Expect the trunk or the order of branches to change at least once.

## Anti-patterns

- Organising by source or by how the work was done (per agent, per file, per sub-report, chronological log) instead of by idea.
- A summary followed by stacked raw reports: a mass of leaves with a trunk glued on.
- Treating "condense" as "shorten".
- Topic headings ("Cost", "Security") where claim headings would carry the message ("Spend accelerated as money ran out").
- A trunk that is three ideas joined by "and".
- Sibling branches that are really stages of one thing, or a working pattern presented as a goal.
- Writing for one audience when the task has two, or writing from your own position when the reader stands somewhere else.
