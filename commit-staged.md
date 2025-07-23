Analyze the currently staged changes and create a commit. You MUST follow these steps exactly:

1. Examine ALL staged files and their diffs to understand what has changed
2. Identify the primary purpose of these changes. If you cannot determine a clear, single purpose from the code alone, you MUST ask for clarification. Do not guess or make assumptions.
3. Evaluate if the staged changes are atomic:
   - If changes address multiple unrelated features/fixes, you MUST suggest splitting into separate commits
   - If the changeset is too large (multiple features, refactoring mixed with features, etc.), you MUST recommend breaking it down
   - When suggesting splits, offer specific guidance on how to unstage/restage files for each logical commit
4. Only after understanding the purpose and confirming the changes are appropriately scoped, write a commit message that:
   - Has a subject line under 50 characters
   - Uses imperative mood ("Add" not "Added")
   - Clearly states WHAT and WHY (not HOW)
   - Includes a blank line and body if more context is needed
5. Present the proposed commit message and explicitly ask: "Should I proceed with this commit?"
6. ONLY execute the commit after receiving explicit approval

CRITICAL: Never commit without understanding the purpose. When in doubt, always ask first.