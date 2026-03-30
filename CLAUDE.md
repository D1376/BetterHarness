## Engineering Defaults
- No overengineering: smallest solution that solves the problem well
- No heavy abstractions, extra layers, or large dependencies for small features
- No cleverness unless it clearly improves the outcome
- Prefer readable, debuggable code over clever code

## Code Hygiene
- Never commit console.log statements
- Single responsibility per module; no mega-files
- No emojis in code or comments

## Compact Instructions
When compressing, preserve in priority order:
1. Architecture decisions (NEVER summarize)
2. Modified files and their key changes
3. Current verification status (pass/fail)
4. Open TODOs and rollback notes
5. Tool outputs (keep pass/fail only)
