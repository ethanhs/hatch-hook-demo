# demo-hook

A demo project with a hatch hook using force-include but not including the files.

To repro:
```
rm -f namespace/dir/.gitignore
hatch build -t wheel
unzip -l dist/*.whl
```