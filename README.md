# mattdb

A simple key-value store written in Go

```sh
export MATTDB_FILE=matt.db
./mattdb put <key> <value>
./mattdb get <key>
```

Options:

| Flag | Environment variable | Description |
|---|---|---|
| -f,--file | MATTDB_FILE | Database file path. |
