
# Video Presentation Script (2-3 minutes)

## 0:00 - Opening Hook
"Most AI trading bots are black boxes. You can't see the logic, can't verify the
decisions, and can't trust the execution. We built something different."

## 0:15 - Problem + Solution
"The crypto trading space needs transparent, risk-aware AI. Not another model
that blindly pumps and dumps. We built QuantAgent — a verifiable, trustless
trading system with on-chain identity."

## 0:30 - Architecture Walkthrough
"Three layers work together:
Role 1: Signal Pipeline — momentum, sentiment, regime detection
Role 2: Strategy Engine — risk-parameterized, adaptive sizing
Role 3: Execution — paper trading with 8-point validation"

## 0:55 - Live Demo
[Show live_demo_paper.py running]
"Watch the agent in action. You can see every signal, every decision, every
risk check in real-time."

## 1:15 - Safety Showcase
"Notice the momentum filter — it blocks entries in downtrends. The circuit
breaker kicks in after consecutive losses. Position sizing adapts to volatility.
This is production-grade risk management."

## 1:35 - ERC-8004 Identity
"Every agent action is recorded as a verifiable artifact. We're using ERC-8004
for agent identity and reputation. Every trade is auditable."

## 1:50 - Trust Signals
"Risk validations, trade proofs, reputation updates — all cryptographically
hashed and stored. Any judge can verify our agent's behavior."

## 2:05 - Why We Should Win
"We didn't just build an AI trader. We built a verifiable, transparent,
risk-aware trading system. It's modular, tested with 135 passing tests,
and ready for production-grade deployment."
