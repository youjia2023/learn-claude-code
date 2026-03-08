# Intermediate Exercises

## Module 6: Skills System

### Exercise 6.1: Understanding Skills
**Objective**: Understand the concept and structure of Skills
**Tasks**:
1. Check what Skills exist in the current project (hint: look at the `.claude/skills/` directory)
2. Read this learning system's SKILL.md and understand its structure
3. Explain the meaning of `name`, `description`, and `disable-model-invocation` fields in the frontmatter

**Checkpoint**: Does the learner understand the Skill file structure and frontmatter configuration?

### Exercise 6.2: Creating Your First Skill
**Objective**: Build a Skill hands-on
**Tasks**:
1. Create a `commit` Skill that helps standardize Git commit message formats
2. Requirements:
   - Automatically check git diff
   - Generate commit messages following Conventional Commits
   - Use `disable-model-invocation: true` (manual invocation only)
3. Test this Skill

**Checkpoint**: Can the learner independently create a working Skill?

### Exercise 6.3: Skill with Supporting Files
**Objective**: Master multi-file Skill structure
**Tasks**:
1. Add a `conventions.md` file to the commit Skill, defining the team's commit message standards
2. Reference this file in SKILL.md
3. Test whether the Skill references the conventions defined in conventions.md

**Checkpoint**: Has the learner mastered the Skill supporting-file mechanism?

---

## Module 7: Debugging Techniques

### Exercise 7.1: Bug Localization
**Objective**: Locate bugs with Claude Code
**Tasks**:
1. The instructor intentionally introduces a bug into the practice project
2. The learner describes the symptoms and asks Claude Code to help locate the issue
3. Learn systematic debugging: gather information → hypothesize → verify → fix

**Checkpoint**: Can the learner effectively describe problems and collaborate with Claude Code to debug?

### Exercise 7.2: Interpreting Error Messages
**Objective**: Learn to leverage error messages
**Tasks**:
1. Ask Claude Code to explain a typical JavaScript error stack trace
2. Ask Claude Code to explain a compilation error
3. Learn how to provide Claude Code with sufficient error context

**Checkpoint**: Has the learner developed the habit of "read the error first, then ask for help"?

---

## Module 8: Refactoring & Optimization

### Exercise 8.1: Code Refactoring
**Objective**: Use Claude Code to refactor code
**Tasks**:
1. Prepare a piece of "bad code" (duplicated code, long functions, etc.)
2. Ask Claude Code to analyze the problems and propose a refactoring plan
3. Ask Claude Code to execute the refactoring
4. Verify that functionality remains unchanged after refactoring

**Checkpoint**: Does the learner understand refactoring principles and Claude Code's refactoring capabilities?

### Exercise 8.2: Performance Optimization
**Objective**: Use Claude Code to analyze and optimize code performance
**Tasks**:
1. Ask Claude Code to analyze a piece of code for performance issues
2. Ask Claude Code to propose optimization strategies
3. Compare the differences before and after optimization

**Checkpoint**: Can the learner get Claude Code to perform targeted optimization?

---

## Module 9: Code Review

### Exercise 9.1: Reviewing Code
**Objective**: Perform code reviews with Claude Code
**Tasks**:
1. Write a piece of "problematic code" (security vulnerabilities, logic errors, style issues)
2. Ask Claude Code to review the code
3. Discuss the issues and suggestions Claude Code found

**Checkpoint**: Does the learner understand the key points of code review and Claude Code's review capabilities?

### Exercise 9.2: Reviewing a PR
**Objective**: Use Claude Code to review Pull Requests
**Tasks**:
1. Create a PR with modifications in the practice project
2. Ask Claude Code to review the PR
3. Understand the review feedback and make changes

**Checkpoint**: Can the learner use Claude Code to perform PR reviews?

---

## Module 10: Efficiency Tips

### Exercise 10.1: Context Management
**Objective**: Master context window management
**Tasks**:
1. Experience what the `/compact` command does
2. Learn when context compression is needed
3. Learn how to stay efficient in long conversations

**Checkpoint**: Does the learner understand the importance of context management?

### Exercise 10.2: Permission Management
**Objective**: Understand Claude Code's permission system
**Tasks**:
1. View the current permission settings
2. Understand allow/deny rules
3. Learn the differences between permission modes

**Checkpoint**: Does the learner understand the importance of permissions for security?
