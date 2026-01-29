First, enter WSL:
```
wsl
```
Run with:
```bash
uv run manim -pql main.py
```
Or optionally, if you want to run only one class of the file:
```bash
uv run manim -pql main.py CreateCircle
```

Git push using:
```bash
git config --global http.postBuffer 524288000
git config --global http.version HTTP/1.1
git push origin master
```