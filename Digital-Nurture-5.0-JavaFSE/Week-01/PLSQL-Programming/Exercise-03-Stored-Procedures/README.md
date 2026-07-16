# PL/SQL Stored Procedures Exercise

## Objective
In this exercise, I worked on PL/SQL stored procedures. It wraps banking transactions and monthly interest application blocks.

## Implementation
### Project Files
* `sample_data.sql` – Database seed script statements
* `schema.sql` – Database schema definitions
* `solution.sql` – PL/SQL procedural statements solution script

### Implementation Details
Created stored procedures with transactional statements like COMMIT and ROLLBACK to transfer balances safely.

## How to Run
```bash
@solution.sql
```

## Expected Output
Running the script creates the procedures and performs sample bank balance transfers.

### Key Takeaways
I understood why wrapping transactions inside stored procedures helps maintain database integrity.
