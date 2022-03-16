# Hotkey
| Hotkey | Outcome |
| :---                  | :---:                    |
| ctrl+arrow key        | Move to next empty cell. |

# Formulas
| Formula | Purpose |
| :---                  | :---:                    |
| VLOOKUP | Row-wise (V for vertical) search. |
| =text(A1, "mm-dd-yy") | Format date in A1 to text. |
| =SPARKLINE(A1:A10, {"charttype", "column" ; "color", "blue"}) | Plot range A1:A10 as a blue column chart that fits a single cell.|
| =COUNTIF(A:A, A1) | Count duplicates of A1 in column A |
| =SUMIF(cond_range, condition, sum_range) | Sum sum_range if cond_range meets condition.|
| =LINEST(y_data, x_data) | Linear fit that returns both SLOPE and INTERSECT. Note that x_range can span multiple columns. |
| =RAND() | Yields a random number. |
| =UNIQUE() | Unique rows in the provided range. Useful when calculating group statistics with COUNTIF, AVERAGEIF, etc.|
| =AVERAGEIF() | Average of values depending on criteria.|
| =FORECAST(x, y_data, x_data) | Expected y-value based on linear regression. | 
| =SORT() | Sort rows of a range by spesified column. |
| =FILTER() | Filters rows based off provided conditions. |





# References
| Reference | Explanation |
| :---                  | :---:                    |
| =A1        | Relative (unlocked) reference to cell A1 |
| =$A1              | Absolute (locked) reference to column A |
| =$A$1             | Absolute (locked) reference to A1|
| ='Sheet Two'!A1 | Reference to cell A1 of 'Sheet Two'. |
| A2:A | Range from A2 to A infinity |

# Concepts
| Concept | Purpose |
| :---                  | :---:                    | 
| Pivot table | Reorganize/Groub by/Summarize/Accumulate data. Also, digging into a pivot table is a handy way to filter/explore datasets.|
| Conditional formatting | Highlight cells based on conditions such as thresholds and matches. Regex available for text conditions.|
| Named ranges | Ranges, and individual cells, can be named, so that they are clearer to use. This also makes references more reliable when, for example, adding new rows within the range.|
| Data validation | Allows to greate interactive checkboxes, dropdown lists, text fields, etc. |
| Hide Column | Hide duplicate columns, for example they might have different formats. |
| Sampling | Use RAND() and Sort by column to sample rows. |