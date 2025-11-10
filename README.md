# PL/SQL Collections, Records, and GOTO - Demo Repository

This repository demonstrates PL/SQL Collections (VARRAY, nested table, associative arrays),
Records (user-defined, %ROWTYPE, cursor-based) and the use of GOTO statements.

## Contents
- `sql/01_create_schema.sql` - create employees table
- `sql/02_insert_sample_data.sql` - populate sample data
- `sql/03_pkg_plsql_demo.sql` - PL/SQL package with demos
- `sql/04_run_tests.sql` - run all demo procedures
- `sql/05_cleanup.sql` - cleanup script
- `docs/ProblemStatement.md` - short problem description
- `docs/AssessmentRubric.md` - grading rubric
- `outputs/expected_output.txt` - sample expected DBMS_OUTPUT

## How to run (Oracle SQL*Plus or SQL Developer)
1. Open SQL*Plus or SQL Developer and connect to your schema.
2. Run `sql/01_create_schema.sql`.
3. Run `sql/02_insert_sample_data.sql`.
4. Run `sql/03_pkg_plsql_demo.sql`.
5. Run `sql/04_run_tests.sql` and observe DBMS_OUTPUT.
6. (Optional) Run `sql/05_cleanup.sql` to remove demo objects.

## Reference
This repository was prepared using the course lecture slides on PL/SQL Collections and Records. :contentReference[oaicite:1]{index=1}
