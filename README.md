┌─────────────────────────────────────────────────────────┐
│                Marketing Agent System                   │
├─────────────────────────────────────────────────────────┤
│  Agent 1     │    Agent 2     │    Agent 3             │
│  (Triage)    │  (Engagement)  │  (Optimization)        │
└─────────────────┬───────────────────────────────────────┘
                  │ 
┌─────────────────▼───────────────────────────────────────┐
│                MCP Server                               │
│         (Handles all database connections)              │
└─────────┬─────────────┬─────────────────┬─────────────────┘
          │             │                 │
          ▼             ▼                 ▼
┌─────────────┐ ┌─────────────────┐ ┌─────────────────┐
│ PostgreSQL  │ │     Redis       │ │     Neo4j       │
│             │ │                 │ │                 │
│ • Leads     │ │ • Sessions      │ │ • Knowledge     │
│ • Campaigns │ │ • Cache         │ │   Graph         │
│ • Long-term │ │ • Short-term    │ │ • Relationships │
│   Memory    │ │   Memory        │ │ • Semantic      │
│ • Analytics │ │ • Real-time     │ │   Memory        │
└─────────────┘ └─────────────────┘ └─────────────────┘




<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ec18995e-277e-447d-801f-77402d63dba0" />
