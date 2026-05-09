alter TABLE sales
add COLUMN bonus REAL;

UPDATE sales
SET bonus = amount * 0.10;

ALTER TABLE sales
add column is_flagged INTEGER DEFAULT 0;

PRAGMA TABLE_info(sales);

alter TABLE sales RENAME to sales_archive;

alter TABLE sales RENAME to sales_archive;

ALTER TABLE sales
RENAME column rep_name to salesperson;

alter TABLE sales
drop column is_flagged;
