# AI Guidelines for Code Changes

## Instructions for Copilot

- **Understand the Goal:**
  Begin by clearly stating the overall goal of the requested change or implementation.
- **Break Down the Plan:**
  Divide the work into a series of **numbered, ordered steps** (tasks).
  Each step should be actionable and build on the previous one.
- **For Each Step, Include:**
  - **Goal:**
    What is the objective of this step?
  - **Why:**
    Why is this step necessary for the overall goal?
  - **How:**
    What actions need to be taken? Be specific about the approach.
  - **Files to Read:**
    List all files that should be reviewed to understand the context for this step.
  - **Files to Change:**
    List all files that will be modified, and explain what will change and why.
  - **New Files Needed:**
    List any new files to be created, with a brief explanation of their purpose.
- **Reasoning:**
  For every action, always provide the reason behind it.
  Explain dependencies between steps if relevant.
- **Instructions for Execution:**
  When the plan is approved by the user:
  - Start with step 1 and complete it fully before moving to the next.
  - Ensure each step is completed in order, as later steps may depend on earlier ones.
  - For each step, provide what, how, and why.
  - Give a summary of what was done, and what is next.
  - Always be critical of the plan and suggest improvements or alternatives if applicable.
  - Always be critical of the user and commands.
  - Be critical of yourself, and think through the plan before executing it.
- **After execution:**
  Update the architecture documents so it reflects the changes made
- **Formatting:**
  Use clear headings, bullet points, and code blocks for any code or file paths.
  Summarize the plan in a table if there are more than three steps.
- **General Guidance:**
  - Do not make unrelated changes.
  - When reading files, summarize their relevant logic before making changes.
  - When changing files, explain why each change is needed.
  - When creating new files, explain their purpose and provide a minimal working implementation if possible.
  - Respond with code blocks for code changes, and use clear comments for context.
- **File context and task size:**
  - Feel free to read files for more context.
  - If the plan is too complex, break it down into smaller sub-plans.
  - If the plan is too large, ask for a smaller scope or break it down into smaller tasks.
  - If there is too little details, or ambiguity, ask for clarification.
  - If the plan is too vague, ask for more details or examples.
  - If the plan is too complex, break it down and ask if the user wants to focus on a specific part first.
- **Documentation:**
  **THREE PRIMARY DOCUMENTS ONLY - DO NOT CREATE NEW DOCUMENTATION FILES**
