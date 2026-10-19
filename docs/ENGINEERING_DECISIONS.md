# Engineering decisions

## Conversation over configuration
The product direction minimizes form-heavy setup. Questions and proposals should appear only when needed to resolve material ambiguity.

## Scale quality to scope
A small item addition and a total world conversion require different review and validation depths.

## Separate creativity from authority
AI can propose code and assets, but tool permissions and validation contracts determine what can be executed or accepted.

## Resource-aware local inference
Interactive work should take priority over background GPU tasks. Heavy models should be scheduled rather than allowed to compete for limited local VRAM.

## Honest maturity claims
The deterministic skin tooling and early controller are described separately from the longer-term goal of fully autonomous mod creation.
