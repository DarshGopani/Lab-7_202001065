# Lab-7_202001065

## Section A:

To design the equivalence class test cases for the program, we need to identify the input conditions that will produce different outcomes. Based on the input ranges provided, we can identify the following equivalence classes:


Valid input dates: This includes all dates that fall within the range specified in the input conditions, i.e., 1 <= day <= 31, 1 <= month <= 12, and 1900 <= year <= 2015. There are a large number of valid dates, but we can choose a representative sample of dates from each month to ensure that we cover all possible scenarios. 

For example:

- January 1, 1900
- Ferbruary 15, 1970
- March 31, 1999
- April 12, 2015
- May 20, 2005
- June 30, 1980
- July 4, 1776 (invalid date)
- August 31, 2010
- September 22, 1960
- October 10, 1995
- November 23, 1985
- December 31, 2012

Invalid input dates: This includes all dates that do not fall within the range specified in the input conditions. There are several possible scenarios that can lead to an invalid date, such as:

- Day is greater than 31
- Month is greater than 12
- Year is less than 1900 or greater than 2015
- February 29 on a non-leap year
- April 31, June 31, September 31, November 31
- Invalid month/day combinations, such as February 30, November 31, etc.

We can choose a few representative examples from each of these scenarios to ensure that we cover all possible cases. 

For example:


- January 32, 2000 (invalid day)
- February 29, 1900 (invalid leap year)
- March 32, 1985 (invalid day)
- April 31, 2010 (invalid day)
- May 13, 500 (invalid year)
- June 31, 2005 (invalid day)
- July 4, 1776 (invalid date)
- August 0, 2012 (invalid day)
- September 31, 1999 (invalid day)
- October 13, -100 (invalid year)
- November 31, 2015 (invalid day)
- December 32, 1980 (invalid day)
These test cases should cover all possible scenarios and ensure that the program can handle both valid and invalid input dates correctly.

