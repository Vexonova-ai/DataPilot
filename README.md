# DataOps Agent

> A production-minded data analytics assistant that lets business users ask questions about their data in natural language — and get **verifiable, evidence-backed answers** without writing SQL.

---

## Overview

Most business users can't write SQL. When a sales manager asks "Why did revenue drop in October compared to September?", they usually need to wait for a data analyst or manually dig through multiple reports.

**DataOps Agent** is not a generic chatbot. It is a **controlled analytics workflow** that:

1. **Understands** the user's question and converts it into a structured analytical request.
2. **Discovers** the right data using a restricted, allow-listed schema context.
3. **Generates and validates SQL** before execution.
4. **Executes read-only queries** in a safe, sandboxed environment.
5. **Presents results** with tables, charts, metric definitions, and explanations grounded in actual query results.

The system never guesses. If it claims a cause for a revenue drop, it must prove it with a breakdown analysis — not a plausible-sounding narrative.
