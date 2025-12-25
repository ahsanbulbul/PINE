# Developer Notes
- Table Schema for articles.db:

```sql
CREATE TABLE articles (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    hash TEXT UNIQUE,
    publisher TEXT,
    title TEXT,
    summary TEXT,
    link TEXT,
    published TEXT,
    language TEXT,
    embedding BLOB
);
```