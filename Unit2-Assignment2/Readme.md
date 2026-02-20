# Unit2-Assignment
## Mixture of Experts (MoE) Router

This project implements a Smart Customer Support Router using the Groq API.

## Architecture
- LLM-based Router (temperature=0) for intent classification
- Domain-specific Experts (technical, billing, general)
- Orchestrator for dynamic expert selection
- Bonus: Tool-use integration (Bitcoin price function)

## Model Used
llama-3.1-8b-instant (Groq)

This demonstrates a modular Mixture of Experts architecture with extensibility via tool integration.
