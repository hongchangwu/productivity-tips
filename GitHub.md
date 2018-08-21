# Markdown

* Escape backticks
  * For backticks in regular text, use `` \` `` (backslash backtick)
  * For backticks in code blocks, use double backticks with
extra spaces, e.g. ```` `` ` `` ````

# Recover a lost commit

```sh
curl -i -H "Accept: application/json" -H "Content-Type: application/json" -X POST -d '{"ref":"refs/heads/<branch>", "sha":"<commit>"}' https://api.github.com/repos/<user>/<repo>/git/refs
```
