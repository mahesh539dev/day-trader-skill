# Daily report 2026-11-20 — NOT RUN
The pipeline could not run: the sandbox network policy blocks the market-data hosts (403 from the agent proxy).
- Blocked: nasdaqtrader.com (universe), feeds.finance.yahoo.com and query2.finance.yahoo.com (news/prices).
- Steps 1-9 produced no results (no universe, no scan, no ORB, no tickets). No orders placed.
Fix: add these hosts to the environment's allowed hosts, then re-run.
