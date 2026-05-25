# Example Run — Contract Warroom

This artifact records a deterministic reviewer demo run for the MiMo approval pattern.

- Project: **Contract Warroom**
- Domain: smart contract security
- Scenario: `vault contract with withdraw ordering and admin privilege risk`
- Status: `completed`
- Mode: `deterministic-reviewer-demo`
- Specialist agents: 5
- Estimated tokens: **41,700**
- Daily projection: **4,003,200 tokens/day**

## Findings

### Liquidity Scout
- Role: tracks pool depth, volatility spikes, and suspicious flow concentration
- Severity: `high`
- Confidence: `0.89`
- Estimated tokens: `9434`
- Finding: Liquidity Scout reviewed DeFi risk monitoring signal: vault contract with withdraw ordering and admin privilege risk. Risk pattern=high confidence=0.89.
- Recommendation: Run liquidity scout follow-up pass, capture artifacts, then prioritize high items first.

### Exploit Sentinel
- Role: maps events to known attack primitives and detects anomalous protocol behavior
- Severity: `high`
- Confidence: `0.78`
- Estimated tokens: `9178`
- Finding: Exploit Sentinel reviewed DeFi risk monitoring signal: vault contract with withdraw ordering and admin privilege risk. Risk pattern=high confidence=0.78.
- Recommendation: Run exploit sentinel follow-up pass, capture artifacts, then prioritize high items first.

### Oracle Auditor
- Role: checks oracle drift, stale feeds, and manipulation windows
- Severity: `high`
- Confidence: `0.88`
- Estimated tokens: `10486`
- Finding: Oracle Auditor reviewed DeFi risk monitoring signal: vault contract with withdraw ordering and admin privilege risk. Risk pattern=high confidence=0.88.
- Recommendation: Run oracle auditor follow-up pass, capture artifacts, then prioritize high items first.

### Treasury Guardian
- Role: scores treasury exposure and proposes emergency controls
- Severity: `low`
- Confidence: `0.91`
- Estimated tokens: `7748`
- Finding: Treasury Guardian reviewed DeFi risk monitoring signal: vault contract with withdraw ordering and admin privilege risk. Risk pattern=low confidence=0.91.
- Recommendation: Run treasury guardian follow-up pass, capture artifacts, then prioritize low items first.

### Incident Reporter
- Role: synthesizes operator-grade markdown incident reports
- Severity: `high`
- Confidence: `0.68`
- Estimated tokens: `4854`
- Finding: Incident Reporter reviewed DeFi risk monitoring signal: vault contract with withdraw ordering and admin privilege risk. Risk pattern=high confidence=0.68.
- Recommendation: Run incident reporter follow-up pass, capture artifacts, then prioritize high items first.

