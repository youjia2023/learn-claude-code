# Advanced Exercises

## Module 11: MCP (Model Context Protocol)

### Exercise 11.1: Understanding MCP
**Objective**: Understand the concept and value of MCP
**Tasks**:
1. Ask Claude Code to explain what MCP is (analogy: installing "plugins" for Claude Code)
2. Understand the difference between MCP and Skills (Skills = how to do things, MCP = new capabilities)
3. List common MCP Servers and their use cases

**Checkpoint**: Does the learner understand MCP's positioning?

### Exercise 11.2: Configuring Context7
**Objective**: Set up your first MCP Server hands-on
**Tasks**:
1. Install the Context7 MCP Server
2. Enable it in Claude Code settings
3. Use Context7 to query documentation for a library (e.g., React, Vue)
4. Experience the difference between having MCP and not having it

**Checkpoint**: Can the learner independently install and configure an MCP Server?

### Exercise 11.3: Configuring Playwright
**Objective**: Set up the browser automation MCP
**Tasks**:
1. Install the Playwright MCP Server
2. Ask Claude Code to open a webpage and take a screenshot
3. Ask Claude Code to perform actions on a webpage

**Checkpoint**: Does the learner understand MCP's powerful extensibility?

---

## Module 12: Hooks Automation

### Exercise 12.1: Understanding Hooks
**Objective**: Understand the concept of Hooks
**Tasks**:
1. Learn about Hook trigger timing (before/after tool calls, notifications, etc.)
2. Review the Hook types supported by Claude Code
3. Understand the difference between Hooks and Skills (Hook = auto-triggered, Skill = manual/intelligent trigger)

**Checkpoint**: Does the learner understand the purpose and trigger mechanism of Hooks?

### Exercise 12.2: Creating a Formatting Hook
**Objective**: Build a Hook hands-on
**Tasks**:
1. Create a Hook that automatically runs code formatting (e.g., prettier) after each file edit
2. Configure the Hook's trigger conditions
3. Test whether the Hook works correctly

**Checkpoint**: Can the learner independently create and debug a Hook?

---

## Module 13: Multi-Agent Collaboration

### Exercise 13.1: Subagent Concepts
**Objective**: Understand Subagents and the Agent tool
**Tasks**:
1. Understand the relationship between the "main Agent" and "Sub Agents"
2. Learn about different Agent types (Explore, Plan, general-purpose)
3. Have Claude Code use the Agent tool to perform a codebase exploration

**Checkpoint**: Does the learner understand the concept of multi-agent systems?

### Exercise 13.2: Parallel Tasks
**Objective**: Work with multiple Agents in parallel
**Tasks**:
1. Design a task that requires parallel processing (e.g., searching multiple directories simultaneously)
2. Have Claude Code execute with multiple Agents in parallel
3. Understand the efficiency gains from parallelism

**Checkpoint**: Does the learner understand the scenarios and methods for parallel execution?

### Exercise 13.3: Team Mode (Advanced)
**Objective**: Experience team mode
**Tasks**:
1. Learn about TeamCreate and team collaboration concepts
2. Try creating a simple team task
3. Understand the mechanisms of team task assignment and coordination

**Checkpoint**: Does the learner have a basic understanding of team mode?

---

## Module 14: Project Management

### Exercise 14.1: Task Management
**Objective**: Manage tasks using Claude Code's Todo system
**Tasks**:
1. Create a task checklist for a small feature
2. Complete tasks in order and update their status
3. Experience task dependencies and blocking relationships

**Checkpoint**: Can the learner manage development tasks with Claude Code?

### Exercise 14.2: Breaking Down Large Projects
**Objective**: Learn to break down complex tasks
**Tasks**:
1. Receive a complex set of requirements
2. Ask Claude Code to help break them down into executable subtasks
3. Use Plan Mode to plan the implementation approach

**Checkpoint**: Has the learner mastered the method of task decomposition?

---

## Module 15: Capstone Project

### Exercise 15.1: Design Your Personal Workflow
**Objective**: Apply everything you've learned to design a complete AI-assisted development workflow
**Tasks**:
1. Analyze pain points in your daily development work
2. Design a workflow incorporating Skills + MCP + Hooks
3. Implement and test this workflow
4. Write a summary document

**Graduation Criteria**:
- Created at least 2 custom Skills
- Configured at least 1 MCP Server
- Created at least 1 Hook
- Can clearly explain the core concepts of Claude Code
- Can independently use Claude Code to complete daily development tasks
