-- question 1

alter table sales
drop COLUMN tier;

alter TABLE sales
add COLUMN tier TEXT DEFAULT 'low';

UPDATE sales
set tier = 'high'
where amount > 1000;

-- question 2

alter table sales
add column tax integer DEFAULT 0;

UPDATE sales
set tax = amount * 0.07
where amount not null;

-- question 3

alter table sales
rename to sales_backup;

alter table sales_backup
rename to sales;

-- question 4

alter TABLE sales
rename product to item;

-- question 5

alter table sales
drop column tier;

PRAGMA table_info(sales);
