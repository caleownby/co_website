---
{"dg-publish":true,"permalink":"/blog/"}
---


# Blog Posts

Formalized blog posts will go here, if you are looking for something a little less refined- check out notes.westho.me

```base
filters:
  and:
    - page_type == "blog_post"
views:
  - type: table
    name: Table
    order:
      - file.name
      - page_type
      - file.ctime
```


Here are some of my previous blog posts 

| File                                                                                                                               | tags                                                             |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [[blog_posts/Doing Agile In Community\|Doing Agile In Community]]                                                               | <ul><li>community</li><li>certifications</li><li>agile</li></ul> |
| [[blog_posts/The hidden cost of Asynchronous Communication\|The hidden cost of Asynchronous Communication]]                     | <ul><li>communication</li><li>teams</li></ul>                    |
| [[blog_posts/Why Teams\|Why Teams]]                                                                                             | <ul><li>teams</li></ul>                                          |
| [[blog_posts/The Merge of Asynchronous and Synchronous Communication\|The Merge of Asynchronous and Synchronous Communication]] | <ul><li>communication</li><li>teams</li></ul>                    |

{ .block-language-dataview}
