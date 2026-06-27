# Agent Safety Literacy Teaching Packet

This packet supports the SIGCSE PCI manuscript "Beyond Prompt Literacy: A Curriculum Framework for Teaching Tool-Using AI Agent Security" (SIGCSE TS 2027).

## Repository Contents

| File | Description |
|------|-------------|
| `README_FIRST.md` | Quick start and navigation guide |
| `sigcse2026_title_screening.csv` | Title-level screening audit for SIGCSE TS 2026 AI/LLM-focused papers (17 papers) |
| `trace_format.md` | JSONL trace field specification (matches Table 7 in the paper) |
| `unit2_course_advising_trace.jsonl` | Synthetic frozen trace for the course-advising running example (Unit 2) |
| `unit2_answer_key.md` | Instructor-facing labels and explanations for the Unit 2 trace |
| `unit4_coding_agent_trace.jsonl` | Synthetic frozen trace matching the paper's coding-agent excerpt (Unit 4) |
| `unit4_coding_agent_answer_key.md` | Instructor-facing labels and explanations for the Unit 4 trace |
| `rubric.md` | Cross-unit assessment rubric with 0-4 scale and unit-specific weights |
| `sandbox_checklist.md` | Mandatory safety checklist for executable labs |
| `red_team_statement.md` | Responsible red-team disclosure and mitigation statement template (Unit 3) |

## Data and Safety Notice

All records, students, tools, credentials, and policies in these traces are **synthetic**. No real student data, API keys, credentials, or production system details are included. The traces are generated from mock environments with no network egress and disposable state.

## Usage

- **Instructors**: Use the trace files for in-class worksheets. The answer keys provide instructor-facing explanations and accepted alternative interpretations.
- **Students**: Use the trace files with the annotation worksheet (not included here; instructors may adapt the format). Students should mark evidence, state assumptions, and compare plausible causes.
- **Executable labs**: Refer to `sandbox_checklist.md` before running any agent code. The non-executable frozen-trace path described in the paper uses these same trace files.

## Citation

If you use these materials, please cite the accompanying SIGCSE PCI paper:

> [Author names]. 2027. Beyond Prompt Literacy: A Curriculum Framework for Teaching Tool-Using AI Agent Security. In *Proceedings of the 58th ACM Technical Symposium on Computer Science Education (SIGCSE TS 2027)*.

## License

[CC BY-NC 4.0 or appropriate open license]