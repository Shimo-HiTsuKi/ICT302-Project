CopyQ/
│
├── main.py
│
├── core/
│   ├── __init__.py
│   ├── analysis_pipeline.py       # NEW
│   ├── data_contract.py           # NEW
│   ├── doc_handler.py
│   ├── integrity_verifier.py      # NEW*
│   ├── docx_unzipper.py
│   ├── xml_parser.py
│   ├── metrics_calculator.py
│   ├── session_manager.py
│   ├── report_generator.py
│   ├── legacy_converter.py        # NEW*
│   └── audit_logger.py            # NEW*
│
├── ui/
│   ├── index.html
│   ├── dashboard.html             # Optional
│   ├── styles.css
│   ├── renderer.js
│   └── assets/
│
├── storage/
│   ├── sessions/
│   └── temp_workspace/
│
├── tests/                         # NEW
│   ├── fixtures/
│   ├── test_doc_handler.py
│   ├── test_integrity.py
│   ├── test_xml_parser.py
│   ├── test_metrics_calculator.py
│   ├── test_session_manager.py
│   ├── test_report_generator.py
│   └── test_end_to_end.py
│
├── README.md
├── requirements.txt
├── .gitignore                     # NEW
└── pyproject.toml                 # Optional
