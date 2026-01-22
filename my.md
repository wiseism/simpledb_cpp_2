# my

```shell
/mnt/d/develops/git/github/cpp/simpledb_cpp_2/cmake-build-debug-wsl24/src/simpledb/parse/parser_unit_tests -r xml -d yes --order lex
Testing started at 14:34 ...
Run with rng-seed=3986716162
```

record
```
add_executable(record_test record_test.cpp)
target_link_libraries(table_scan_test simpledb_server)
```

```shell
[  6%] Built target simpledb_file
[ 16%] Built target simpledb_parser
[ 19%] Built target simpledb_log
[ 32%] Built target simpledb_query
[ 35%] Built target simpledb_buffer
[ 51%] Built target simpledb_tx
[ 58%] Built target simpledb_record
[ 74%] Built target simpledb_index
[ 83%] Built target simpledb_metadata
[ 96%] Built target simpledb_plan
[ 96%] Built target simpledb_server
```

add_executable(index_select_test
query/IndexSelectTest.cpp
)

target_link_libraries(index_select_test
PRIVATE
simpledb_server
)