```bash
career-compass/
├── config/                      # Configuration files
│   ├── agent_config.yaml        # Agent-specific configurations
│   ├── app_config.yaml          # Application-level settings
│   └── model_config.yaml        # LLM and embedding model configs
│
├── agents/                      # Agent implementations
│   ├── base_agent.py            # Base agent class with common functionality
│   ├── resume_agent.py          # Resume analysis agent
│   ├── job_search_agent.py      # Job search and matching agent
│   ├── cover_letter_agent.py    # Cover letter generation agent
│   ├── workflow_agent.py        # Workflow coordination agent
│   └── specialized/             # Optional specialized agents
│       ├── interview_agent.py
│       └── tracking_agent.py
│
├── workflows/                   # LangGraph workflow definitions
│   ├── graph_definitions.py     # Graph structure definitions
│   ├── states.py                # State management
│   ├── nodes.py                 # Workflow node definitions
│   └── transitions.py           # State transition logic
│
├── rag/                         # RAG implementation
│   ├── document_processor.py    # Document parsing and processing
│   ├── vector_store.py          # Vector database interface
│   ├── embeddings.py            # Embedding generation
│   ├── retrieval.py             # Retrieval strategies
│   └── knowledge_bases/         # Pre-built knowledge bases
│       ├── resume_templates/
│       ├── job_market/
│       └── industry_knowledge/
│
├── tools/                       # Utility tools for agents
│   ├── pdf_parser.py            # PDF handling
│   ├── docx_parser.py           # Word document handling
│   ├── job_scraper.py           # Job board scraping
│   ├── text_analyzer.py         # Text analysis utilities
│   └── formatting.py            # Output formatting
│
├── data/                        # Data storage
│   ├── schema/                  # Data schemas
│   ├── user_data/               # User-specific data storage
│   └── cached_data/             # Cached job listings, etc.
│
├── api/                         # API layer (optional)
│   ├── routes.py                # API endpoints
│   └── middleware.py            # API middleware
│
├── tests/                       # Test suite
│   ├── unit/                    # Unit tests
│   ├── integration/             # Integration tests
│   └── fixtures/                # Test data
│
├── utils/                       # Utility functions
│   ├── logging.py               # Logging configuration
│   ├── error_handling.py        # Error handling utilities
│   └── evaluation.py            # Evaluation metrics
│
├── main.py                      # Application entry point
├── requirements.txt             # Project dependencies
└── README.md                    # Project documentation
```
