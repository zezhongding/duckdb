### Clone the DuckDB repository
```bash
$ git clone https://github.com/duckdb/duckdb
```

### Install the required packages with the package manager of your distribution.

```bash
$ sudo apt-get update && sudo apt-get install -y git g++ cmake ninja-build libssl-dev
```
### Build DuckDB
```bash
$ GEN=ninja make
```
