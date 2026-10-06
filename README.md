# json2dir-cforall

[json2dir](https://github.com/kitsunoff/awesome-json2dir) in [Cforall](https://cforall.uwaterloo.ca): reads a JSON document on stdin and creates the directory tree it describes in the current directory.

    cfa -O2 json2dir.cfa -o json2dir && ./json2dir < tree.json
