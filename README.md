# SQLFluff config

[SQLFluff](https://docs.sqlfluff.com/en/stable/)

A sample SQLFluff config, complete with `ignore` file, and generator to take table metadata and input into main `sqlfluff` file

Install via `pip`:

```bash
pip install sqlfluff
```

Run file fix via:

```bash
sqlfluff fix test.sql
```

Ideally used within pre-commit pipeline
