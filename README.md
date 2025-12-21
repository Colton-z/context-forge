# Context Forge

**Turn your ETL pipelines into living documentation.**

Context Forge automatically reconstructs business logic from data lineage (DDL + ETL SQL), generating continuously fresh context for AI Agents—without anyone writing a single doc.

> 📄 Read the full methodology: [ETL as Documentation: Building Self-Updating Enterprise Context via Data Lineage](https://medium.com/@zhenchangqi/etl-as-documentation-building-self-updating-enterprise-context-via-data-lineage-e9c1f7c934f4)

---

## The Problem

Enterprise AI Agents hallucinate because they lack business context. Documentation is always stale—no one maintains it. But there's one place where business logic *must* stay accurate: **your ETL code**. Every metric, every KPI, every dashboard is computed by SQL that someone *has* to keep up to date.

## The Solution

Context Forge extracts the full upstream lineage of your KPI dashboards, structures it by warehouse layer (ODS → DWD → DWS → ADS), and feeds it to an LLM to reconstruct business logic. The output: a comprehensive, auto-updating business knowledge base that powers your Agents.
