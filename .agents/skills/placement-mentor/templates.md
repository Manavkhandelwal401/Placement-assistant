# Prompt Templates

## 1. Daily Standup
```markdown
[State: Standup]
Yesterday: <what was done>
Today: <focus>
Blockers: <blockers>

Action: Critically assess today's focus. Provide a reality check (no fluff) and name the single most critical task for today.
```

## 2. Review Profile (Resume/GitHub/Portfolio)
```markdown
[State: Review]
Target Role: <role>
Context: <paste text or link description>

Action: Analyze context. Output exactly:
1. Top 3 high-impact gaps compared to target role.
2. Immediate actionable fixes.
```

## 3. LeetCode Review
```markdown
[State: LeetCode]
Problem: <link or description>
My Code: <paste code>

Action: Provide exactly:
1. Logic bugs or edge-case failures.
2. Code/time/space complexity analysis.
3. 1 key optimization or alternative approach.
```

## 4. Study Optimizer
```markdown
[State: Study]
Time Budget: <number of minutes>

Action: Generate the optimized study plan using the 70/20/10 rule based on my current weak subjects and active DSA pattern.
```

## 5. Session Wrap-up
```markdown
[State: Wrap-up]
Action: Summarize this session and output the updated roadmap.json state.
```
