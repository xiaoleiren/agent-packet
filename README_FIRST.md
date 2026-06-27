# Quick Start Guide

## For Instructors

1. **Start here**: Read the paper's Section 5 (Curriculum Framework) for the module overview.
2. **Choose your path**:
   - **Non-executable (recommended for first-time adoption)**: Use the frozen trace files (`unit2_*.jsonl`, `unit4_*.jsonl`) with worksheets. No live LLM access or agent infrastructure needed.
   - **Executable**: Follow `sandbox_checklist.md` before running any agent code.
3. **Review materials**:
   - `trace_format.md` — explains JSONL field structure
   - `rubric.md` — scoring guide for all units
   - `red_team_statement.md` — ethics template for Unit 3
4. **For Unit 2**: Use `unit2_course_advising_trace.jsonl` + `unit2_answer_key.md`
5. **For Unit 4**: Use `unit4_coding_agent_trace.jsonl` + `unit4_coding_agent_answer_key.md`

## File Naming Convention

- `unitX_*.jsonl` — synthetic frozen traces for Unit X
- `unitX_*_answer_key.md` — instructor-facing answer keys
- `*.md` — documentation and templates

## Quick Reference: Trace Fields

| Field | Purpose |
|-------|---------|
| `event_id` | Unique event identifier |
| `timestamp` | Event ordering |
| `source_channel` | `developer_policy`, `user_instruction`, `retrieved_input`, or `tool_output` |
| `tool` | Tool name invoked |
| `arguments` | Tool arguments |
| `return_value` | Tool return data |
| `policy_check` | `allowed`, `denied`, `missing`, or `human_gate` |
| `student_note` | (Student-filled) annotation field |

See `trace_format.md` for full specification.