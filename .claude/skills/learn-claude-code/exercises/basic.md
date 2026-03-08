# Basic Exercises

## Module 1: Introduction to Claude Code

### Exercise 1.1: First Conversation
**Objective**: Learn to converse naturally with Claude Code
**Tasks**:
1. Ask Claude Code to introduce itself
2. Ask Claude Code what the current working directory is
3. Ask Claude Code to list the files in the current directory

**Checkpoint**: Can the learner communicate naturally with Claude Code?

### Exercise 1.2: Understanding Context
**Objective**: Understand what Claude Code can see
**Tasks**:
1. Ask Claude Code to read a file in the project
2. Ask Claude Code "Can you see the files on my desktop?" (Correct answer: No, it can only see the working directory)
3. Ask Claude Code to explain its "field of vision"

**Checkpoint**: Does the learner understand Claude Code's context boundaries?

---

## Module 2: File Operations

### Exercise 2.1: Reading Files
**Objective**: Master the Read tool
**Tasks**:
1. Ask Claude Code to read `README.md`
2. Ask Claude Code to read a file that doesn't exist — observe the error message
3. Ask Claude Code to read only the first 10 lines of a file

**Checkpoint**: Does the learner know how to instruct Claude Code to read files?

### Exercise 2.2: Creating Files
**Objective**: Master the Write tool
**Tasks**:
1. Ask Claude Code to create a `hello.js` file that prints "Hello World"
2. Ask Claude Code to create a `src/utils/helper.js` file (note: the directory may not exist)
3. Verify the files were created correctly

**Checkpoint**: Can the learner get Claude Code to create structured files?

### Exercise 2.3: Editing Files
**Objective**: Master the Edit tool
**Tasks**:
1. Ask Claude Code to modify `hello.js`, changing "Hello World" to "Hello Claude Code"
2. Ask Claude Code to add a comment at the end of the file
3. Understand the difference between Edit and Write

**Checkpoint**: Does the learner understand Edit (partial modification) vs Write (full replacement)?

### Exercise 2.4: Search Operations
**Objective**: Master Glob and Grep
**Tasks**:
1. Ask Claude Code to find all `.md` files in the project
2. Ask Claude Code to search for files containing the keyword "learn"
3. Ask Claude Code to search for which files a specific function name appears in

**Checkpoint**: Does the learner know the difference between Glob (find filenames) and Grep (find content)?

---

## Module 3: Command Line Operations

### Exercise 3.1: Basic Bash Usage
**Objective**: Understand when to use the Bash tool
**Tasks**:
1. Ask Claude Code to run `node hello.js`
2. Ask Claude Code to check the git status
3. Discussion: When should you use Bash vs. dedicated tools?

**Checkpoint**: Does the learner understand the division between Bash tool and dedicated tools?

---

## Module 4: CLAUDE.md

### Exercise 4.1: Creating CLAUDE.md
**Objective**: Understand the concept of project memory
**Tasks**:
1. Use the `/init` command to let Claude Code auto-generate a CLAUDE.md
2. Read the generated content and understand each section
3. Manually add a project convention (e.g., "This project uses Simplified Chinese for comments")

**Checkpoint**: Does the learner understand the purpose and format of CLAUDE.md?

### Exercise 4.2: Configuration Hierarchy
**Objective**: Understand CLAUDE.md at different locations
**Tasks**:
1. Learn the difference between `~/.claude/CLAUDE.md` (global) and the project-level `CLAUDE.md`
2. Add personal preference settings to the global CLAUDE.md
3. Verify that Claude Code can read these configurations

**Checkpoint**: Does the learner understand the configuration priority?

---

## Module 5: Daily Workflows

### Exercise 5.1: Writing Code
**Objective**: Experience the full workflow of writing code with Claude Code
**Tasks**:
1. Ask Claude Code to create a simple TODO app (plain JS)
2. Ask Claude Code to add a new feature to the code
3. Ask Claude Code to fix a bug you intentionally introduced

**Checkpoint**: Can the learner use Claude Code to complete a full development task?

### Exercise 5.2: Git Operations
**Objective**: Master version control through Claude Code
**Tasks**:
1. Ask Claude Code to check the current git status
2. Ask Claude Code to stage and commit your changes
3. Ask Claude Code to create a new branch

**Checkpoint**: Can the learner perform basic Git operations through Claude Code?
