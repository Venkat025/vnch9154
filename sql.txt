CURRENT_DATE: Returns the current date.
Example: SELECT CURRENT_DATE;

CURRENT_TIME: Returns the current time.
Example: SELECT CURRENT_TIME;

CURRENT_TIMESTAMP: Returns the current date and time.
Example: SELECT CURRENT_TIMESTAMP;

EXTRACT: Extracts a specific part (year, month, day, etc.) from a date or timestamp.
Example: SELECT EXTRACT(YEAR FROM my_date_column) FROM my_table;

DATEADD: Adds a specific interval to a date or timestamp.
Example: SELECT DATEADD(DAY, 7, my_date_column) FROM my_table;

DATEDIFF: Calculates the difference between two dates or timestamps.
Example: SELECT DATEDIFF(DAY, start_date, end_date) FROM my_table;

DATEPART: Returns a specific part (year, month, day, etc.) from a date or timestamp.
Example: SELECT DATEPART(MONTH, my_date_column) FROM my_table;

DATE_FORMAT: Formats a date or timestamp according to a specific format.
Example: SELECT DATE_FORMAT(my_date_column, '%Y-%m-%d') FROM my_table;