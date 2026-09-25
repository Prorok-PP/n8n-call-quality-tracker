## Problem
Support teams record hundreds of calls but can review only a few of them.
Quality problems stay invisible until a customer complains.
 
## Solution
An n8n pipeline transcribes each call with AssemblyAI, scores it against a
QA rubric with an LLM, and stores the result in an n8n Data Table.
A second workflow returns statistics for any date range, and an AI agent
answers managers' questions about team performance in plain language.
 
## Tech stack
n8n | AssemblyAI | OpenAI | n8n Data Tables | AI Agent
