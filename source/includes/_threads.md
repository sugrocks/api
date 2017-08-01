# Threads

```json
{
  "_": {
    "generated": 1501593002
  },
  "co": {},
  "trash": {
    "10771362": {
      "archive": "https://desuarchive.org/trash/thread/10771362",
      "board": "trash",
      "dates": {
        "RFC822": "Tue,  1 Aug 2017 03:59:29Z",
        "atom": "2017-08-01T03:59:29Z",
        "string": "08/01/17(Tue)03:59:29(UTC)",
        "timestamp": 1501559969
      },
      "edition": "Meekface Edition",
      "id": 10771362,
      "media": {
        "deleted": false,
        "height": 1449,
        "name": "1491774395468.png",
        "spoiler": false,
        "url": "http://i.4cdn.org/trash/1501559969868.png",
        "width": 1280
      },
      "op": "/sug/ - Steven Universe General<br><br>Meekface Edition<br><br>Last Thread: [snip]",
      "page": "0",
      "status": {
        "archived": false,
        "bump_limit": true,
        "closed": true,
        "dead": true,
        "image_limit": false
      },
      "url": "http://boards.4chan.org/trash/thread/10771362"
    },
    "10775044": {
      "archive": "https://desuarchive.org/trash/thread/10775044",
      "board": "trash",
      "dates": {
        "RFC822": "Tue,  1 Aug 2017 07:59:11Z",
        "atom": "2017-08-01T07:59:11Z",
        "string": "08/01/17(Tue)07:59:11(UTC)",
        "timestamp": 1501574351
      },
      "edition": "Mustard Edition",
      "id": 10775044,
      "media": {
        "deleted": false,
        "height": 630,
        "name": "NOOOOOOOOOOOOOO MI MUSTARD.png",
        "spoiler": false,
        "url": "http://i.4cdn.org/trash/1501574351807.png",
        "width": 600
      },
      "op": "/sug/ - Steven Universe General<br><br>Mustard Edition<br><br>Last Thread: [snip]",
      "page": 11,
      "status": {
        "archived": false,
        "bump_limit": true,
        "closed": false,
        "dead": false,
        "image_limit": false
      },
      "url": "http://boards.4chan.org/trash/thread/10775044"
    }
  }
}
```

This endpoint retrieves all threads.

### HTTP Request

`GET https://api.sug.rocks/threads.json`

<aside class="notice">In this example, the first thread is already dead (404), so you should link to the archive instead of the url. The second example did reach the bump limit but is still available.</aside>
