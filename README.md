# LiveRegent – Real-Time Regulatory Intelligence Agent

LiveRegent is an agentic AI system designed to reason over continuously evolving regulatory and policy documents using Pathway’s streaming engine.

## Problem
Traditional RAG pipelines rely on batch ingestion and static embeddings, causing AI systems to reason over stale data. This creates compliance risks in environments where regulations change frequently.

## Solution
LiveRegent maintains an always-current knowledge state by:
- Continuously ingesting live documents using Pathway
- Incrementally updating only modified sections
- Performing multi-step agentic reasoning over fresh context

## System Architecture
The system consists of:
- Live Data Sources (PDFs, portals, feeds)
- Pathway Streaming Engine for change detection
- Live Knowledge Index with incremental updates
- Agent Orchestrator for planning and tool use
- LLM Reasoning Layer for analysis and decisions 

## Current Stage
This repository represents the **proposal and system design phase** of the project.  
Implementation will follow in later rounds.

## Future Work
- Full agent implementation using Pathway
- Live compliance demo
- Integration with Dragon Hatchling (BDH) as the reasoning layer for continuous learning and interpretability

## Track
Track 1 – Agentic AI (Applied GenAI)

## Team
pdpathak2005