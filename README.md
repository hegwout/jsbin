# Fixes for the sandbox database
```sql
ALTER TABLE sandbox ALTER COLUMN streaming_read_key SET DEFAULT '';
ALTER TABLE sandbox ALTER COLUMN active_cursor SET DEFAULT 0;

ALTER TABLE sandbox ALTER COLUMN active_cursor SET DEFAULT 0;
ALTER TABLE sandbox ALTER COLUMN active_tab SET DEFAULT '';
```