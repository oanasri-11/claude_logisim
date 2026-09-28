 # Global Architecture :
                      LOGISIM
                       │
        ┌──────────────┼──────────────┐
        │              │              │
        ▼              ▼              ▼
   Circuit Model    UI / GUI      Simulation
        │
        │
        ▼
   AI Integration
        │
        ├── Circuit → JSON
        │
        ├── Context Manager
        │
        ├── Tool System
        │
        └── Claude API
                  │
                  ▼
              Claude
