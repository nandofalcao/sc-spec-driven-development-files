---
name: feature-spec-checklist
description: Kicks off a new feature by finding the next incomplete phase in specs/roadmap.md, creating a git branch, interviewing the user about scope/decisions/context, and writing a dated spec directory with requirements.md, plan.md (checklist format for agent progress tracking), and validation.md.
---

# Feature Spec (Checklist)

## Workflow

### 1. Find the next phase

Read `specs/roadmap.md`. The next phase is the first section whose items are all `[ ]`. Note its name to derive the branch and directory name.

### 2. Create the branch

```
git checkout -b phase-N-<kebab-name>
```

### 3. Interview the user — BEFORE writing any files

Use `AskUserQuestion` with exactly **3 questions in one call**:

| Header | Question focus |
|--------|---------------|
| **Scope** | What the feature collects, exposes, or does — fields, behaviour, data shape |
| **Decisions** | Key implementation choices — storage, visibility, validation, UX pattern |
| **Context** | Tone, constraints, or anything shaping the spec — copy style, stack limits, open questions |

Do **not** write any files until the user has answered all three questions.

### 4. Read guidance files

Read `specs/mission.md` and `specs/tech-stack.md` before drafting.

### 5. Create the spec directory

Name: `specs/2026-04-26-<feature-name>/` using today's date.

#### `requirements.md`
- Scope section: what is and is not included; field/data table if applicable
- Decisions section: choices made and why (draw from user answers)
- Context section: tone rules, stack pointers, existing patterns to follow

#### `plan.md`
- Task groups appropriate to the feature (for example: Data → Components → Page & Route → Navigation → Tests)
- Each group contains sub-tasks written as **Markdown checkboxes** (`- [ ] task description`)
- Groups should be independently implementable
- The agent **must mark each checkbox as done** (`- [x]`) immediately after completing that task — do not batch-update at the end
- Example structure:

```markdown
## Group 1: Data

- [ ] Create migration file
- [ ] Add seed entry

## Group 2: Components

- [ ] Build form component
- [ ] Add validation logic
```

#### `validation.md`
- Automated: project test and typecheck commands pass; specific assertions required
- Manual: walkthrough, behaviour, edge cases
- Tone check if the feature has user-facing copy
- Definition of done

## Constraints

- Respect the existing tech stack defined in `specs/tech-stack.md` — no new dependencies without user approval
- Follow existing conventions and patterns already established in the codebase
- Keep feature scope focused and independently shippable
- When executing tasks from `plan.md`, always update the checkbox (`- [x]`) right after finishing each sub-task
