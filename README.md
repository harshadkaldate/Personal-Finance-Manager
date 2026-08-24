# Personal Finance Manager

A production-ready, highly robust terminal-based personal finance management application written in pure C11. No external databases or GUI dependencies required. It tracks transactions, models category analysis, enforces budget caps, and acts as a localized CLI data interface.

## Features
* **Full CRUD Operations**: Add, Edit, Delete, Search, and View transactions effortlessly.
* **Persistent Binary Storage**: Automated data loading/saving leveraging optimized binary file operations (`.dat`).
* **Modular Analytics**: Get immediate insights on savings projections, budget threshold warnings, and category disbursements. 
* **Reliability Checkers**: Bullet-proof memory mapping and input sanity filters to prevent buffer overflows or software crashes.
* **Intelligent Exports**: Compiles standard localized `.txt` reports autonomously.

## Folder Structure
FinanceManager/
│
├── main.c           # System entry and UI loop
├── finance.h        # Structures, globals, definitions
├── transaction.c    # Transaction domain logic (CRUD)
├── analytics.c      # Statistics, Reports, Budgets
├── storage.c        # File I/O serialization
├── utils.c          # Formatter, Screen config, Date/Time
├── validation.c     # Data guardrails
├── Makefile         # Build directives
├── README.md        # Documentation
│
├── data/            # Stores transactions.dat
└── reports/         # Output directory for .txt reports.
