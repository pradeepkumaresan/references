### command to rename all files matching a pattern to another name

```find . -type f -name "references.md" -exec sh -c 'mv "$1" "${1%/*}/README.md"' sh {} \;```
