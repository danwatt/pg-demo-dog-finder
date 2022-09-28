## Pets Demo

### Purpose

This is a demonstration of adding an "unknown" value to eliminate the need to search for something that does not
exist, thus eliminating a `LEFT JOIN`.

## Startup

```bash
make run
```

On startup, the database will be populated with a schema, some CSV reference data, and some randomly created dogs.
Additionally, if you look at the console output, you will see the results of three queries
in [04-queries.sql](./sql/04-queries.sql).

If you want to explore the data further, connect your favorite database client to: `postgresql://localhost:5432/postgres`
with username `postgres` and password `password`.

## 3rd Party Data License Notice

Data is licensed under the MIT License. Data is provided
by [akcdata](https://github.com/tmfilho/akcdata).

```
MIT License

Copyright (c) 2020 Telmo Filho

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```