# issue-comment-actions

```yml
on:
  issues:
    types: [opened]

jobs:
  greet:
    runs-on: ubuntu-latest
    name: Issue comment
    steps:
      - name: issue comment
        uses: kyoncy/issue-comment-actions@v1
```
