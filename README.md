# 21-savage

## Description

**21-savage** is a strategic and calculated player in the Iterated Prisoner's Dilemma tournament. It starts with a peaceful gesture — cooperating on the first move — but quickly turns ruthless when betrayed.

- **Opening Move**: Always cooperates.
- **Opponent Cooperates**: Continues cooperating.
- **Opponent Defects**:
  - Immediately begins a punishment cycle: two defections followed by one cooperation.
  - This 3-move punishment cycle (`D, D, C`) repeats each time the opponent defects again.
