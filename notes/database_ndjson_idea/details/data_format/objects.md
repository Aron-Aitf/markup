`rows` are ndjson objects in a file (`table`)

## Why ndjson?

ndjson can be parsed line-by-line (`stream processing`)

for example, when sequentially filtering for a value:
  the data can be read in blocks or lines (whichever is larger) then filtered without loading anything into memory (use libraries for stream processing the file)
for examples, see [[folder_structure]]