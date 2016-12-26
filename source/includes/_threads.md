# Threads

```json
[
  {
    "id": 26886430,
    "board": "trash",
    "timestamp": 1482654547,
    "edition": "It's Christmas Edition",
    "page": 7,
    "status": {
      "bump_limit": true,
      "image_limit": false,
      "archived": false
    },
    "url": "https://boards.4chan.org/trash/thread/6886430",
    "archive": "https://desuarchive.org/trash/thread/6886430",
    "media": "https://is.4chan.org/trash/1482654547608s.jpg",
    "op": "\/sug\/ - Steven Universe General<br><br>It&#039;s Christmas Edition[snip]"
  },
  {
    "id": 94921,
    "board": "sugen",
    "timestamp": 1480547635,
    "edition": "Not Steven Universe Edition",
    "page": null,
    "status": {
      "bump_limit": false,
      "image_limit": false,
      "archived": false
    },
    "url": "https://8ch.net/sugen/res/94921.html",
    "archive": null,
    "media": "https://media.8ch.net/file_store/thumb/f44639d20cc93eac99d5ea6d67fbb5d7cdbf567f0313ca221ca0b81aa12762aa.png",
    "op": "<p class=\"body-line ltr \">Not Steven Universe Edition <\/p>[snip]"
  }
]
```

This endpoint retrieves all threads.

### HTTP Request

`GET htts://sug.rocks/api/threads.json`

<aside class="notice">/sugen/ don't return anything for `page` and `archive`.</aside>
