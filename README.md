<h3 align="center">sql-query-optimization</h3>

The optimized query can be found in <i>optimised-query</i> file in this project.

In this optimized version, Following are the improvments made:

- I have removed unnecessary LEFT JOINs that weren't contributing to the search criteria. This reduces the complexity of the query and improves performance.
- I retained INNER JOINs for essential relationships (jobs to job categories and job types).
- I also ensured that the WHERE clause is focused on indexed columns to improve query performance.

#### Time Taken
2 Hours


