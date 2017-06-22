# LJ Code 301 - Day 8

On day 8, I learned a few Structured Query Language (SQL) queries. For instance, the following statement selects all people with a name startin with "N".

```sql
SELECT * FROM people WHERE name LIKE "N%"
```

The "%" symbol is a wildcard matching zero or more characters. "_" can also be used as a wildcard matching a single character. In this way, you can specify how many unknown characters you want to match by the number of underscores.

You can also limit the results with "LIMIT" and set which row to start the query with "OFFSET".

After we learned this, we built a full stack web app using postgres.