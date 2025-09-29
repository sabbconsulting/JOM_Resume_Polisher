CHANGELOG

v2.0 (Current Release)

🛡️ Enhanced Safety & Accuracy
- Strengthened safeguards against AI making unauthorized changes to factual content (dates, employers, education, job titles)
- All modifications require user review and approval before implementation
- Removed Quick Mode - eliminated fast polish option that could make changes without user oversight
- Added explicit triage process - AI must evaluate what needs user input vs. what can be fixed directly before asking questions
- Limited questions to 1-3 maximum per cycle to avoid overwhelming users

🎯 Expert-Based Evaluation
- Added comprehensive Expert Knowledge Base covering:
  - ATS systems (file format, parsing, keywords)
  - Human reviewers (recruiter screening patterns, career tracking)
  - Resume writing best practices (accomplishments vs. responsibilities, quantification)
- Updated rating scale with explicit, expert-sourced criteria:
  - Needs Work: Clear definitions of major problems
  - Developing: Specific gaps that need addressing
  - Strong: Concrete standards for interview-ready resumes
  - Outstanding: Exceptional criteria that impress demanding hiring managers
- Dual-lens evaluation: Analyzes resumes through both ATS and Human reviewer perspectives

⚡ Streamlined Workflow
- Removed mode selection - now runs single standard workflow
- Simplified pre-flight check - proceeds directly to analysis after resume upload
- Dynamic question generation - replaces rigid flag categories with contextual questions based on actual resume needs
- Smarter recommendation handling - distinguishes between what AI can fix directly vs. what genuinely needs user input
- Clearer loop controller - improved question: "Would you like to continue working on the resume, or are you ready for the final copy?"
- Reorganized output flow - moved output rules after loop controller for logical workflow sequence

📊 Evidence-Based Best Practices
- Focuses on accomplishments over responsibilities with quantified results
- Incorporates proven action-verb guidance - replaces overused words with impactful alternatives
- Impact-focused bullet point structure - uses "Action + Project + Result" formulas
- Based on current hiring research - all practices sourced from expert studies of recruiters and hiring managers

🗑️ Removed Features
- Quick Mode (fast polish without user input)
- Guided Mode naming (now just "standard workflow")
- Pre-defined Decision Flags (replaced with dynamic questions)
- Vague "preserve authenticity" rule
- Generic ATS rule (replaced with comprehensive expert knowledge)
- Redundant sections (Brand Alignment Notes, Starter Prompt)
- "Parking Lot" concept (unused in practice)

---

v1.0.1 (Previous Release)

Features
- Two-mode operation: Quick Mode and Guided Mode
- Analyzer-Refiner workflow loop
- Pre-flight resume check
- Decision Flags for common missing information
- Cross-platform output support (ChatGPT file downloads, Copy Block for other platforms)
- Sandbox mode (no memory, no project files)
- Basic rating scale: Weak, Moderate, Competitive, Top Tier
- Core safety rules against fabrication

