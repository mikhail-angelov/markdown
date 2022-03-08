# Simple markdown online editor

markdown is base on [remarkable engine](https://github.com/jonschlinkert/remarkable)
diagrams is based on [pintora](https://github.com/hikerpig/pintora)

## [Online markdown editor](https://mikhail-angelov.github.io/markdown)

You can draw diagram by annotating `pintora` for the code fence
~~~markdown
```pintora
sequenceDiagram
  State1-->>State2: action1
  @note over State1,State2: some note
  @note right of State2
  multiline
  note
  @end_note
```
~~~
![markdown preview](https://raw.githubusercontent.com/mikhail-angelov/markdown/3f38128ea3a06376950a9bb6ecca6131157c7905/screen.png)