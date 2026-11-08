## Task 5.1 — Terminal Navigation

- `pwd` — printed current directory
- `mkdir -p my-project/src/{css,js,images} my-project/docs my-project/tests` — created nested folders
- `touch my-project/README.md` — created empty README file

## Task 5.3 - Useful Commands
`How many HTML files`
find . -name "*.html" | wc -l

`Which files contain "contact"?`
grep -rl "contact" .

`How many lines is your CSS file?`
wc -l css/styles.css

`Last 10 terminal commands?`
history | tail -10


