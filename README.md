## Project Structure

```bash
student-feedback-manager/
│
├── feedback_entry.py               # Collect student feedback
├── score_calculator.py             # Compute average score
├── feedback_summary.py             # Summarise feedback (v1.0.1)
├── report_generator.py             # Export feedback to txt (v1.1.0)
├── search_feedback.py              # Search feedback by student name (v1.2.0)
├── count_feedback.py               # Count total entries (v1.2.0)
│
├── tests/                          # Test cases for all features
│   ├── test_feedback_entry.py
│   ├── test_score_calculator.py
│   ├── test_feedback_summary.py
│   ├── test_report_generator.py
│   ├── test_search_feedback.py
│   └── test_count_feedback.py
│
├── .github/
│   └── workflows/
│       └── python-app.yml          # GitHub Actions Workflow for pytest
│
├── README.md                       # Project Overview & Roadmap
├── LICENSE                         # License file
├── CONTRIBUTING.md                 # Contribution guidelines
├── CODE_OF_CONDUCT.md              # Code of conduct
├── CHANGELOG.md                    # Version-wise updates
├── TEAM_LOG.md                     # Team contributions log
│
└── requirements.txt                # Python dependencies (if any)
