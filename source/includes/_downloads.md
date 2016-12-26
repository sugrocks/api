# Downloads

```json
[
  {
    "preair": [
      {
        "id": 1,
        "season": 1,
        "episode": 1,
        "title": "episode title",
        "url": "https://example.com/preair/ep.mkv",
        "marebucks": "https://marebucks.com/sun/",
        "dailymotion": "https://dailymotion.com/",
        "torrent": null
      }
    ]
  },
  {
    "itunes": [
      {
        "id": 1,
        "season": "1",
        "episode": "1_2",
        "title": "Gem Glow & Laser Light Cannon",
        "url": "https://example.com/01x01_02.mkv",
        "marebucks": "https://marebucks.com/sun/1",
        "dailymotion": null,
        "torrent": "https://example.com/torrents/01x01_02.mkv.torrent"
      },
      {
        "id": 2,
        "season": "1",
        "episode": "3_4",
        "title": "Cheeseburger Backpack & Together Breakfast",
        "url": "https://example.com/01x03_04.mkv",
        "marebucks": "https://marebucks.com/sun/3",
        "dailymotion": null,
        "torrent": "https://example.com/torrents/01x03_04.mkv.torrent"
      },
    ]
  },
  {
    "individual": [
      {
        "id": 1,
        "season": "1",
        "episode": "1",
        "title": "Gem Glow",
        "url": "https://example.com/mega/01x01.mp4",
        "marebucks": "https://marebucks.com/sun/1",
        "dailymotion": null,
        "torrent": null
      },
      {
        "id": 2,
        "season": "1",
        "episode": "2",
        "title": "Laser Light Cannon",
        "url": "https://example.com/mega/01x02.mp4",
        "marebucks": "https://marebucks.com/sun/2",
        "dailymotion": null,
        "torrent": null
      },
    ]
  }
]
```

This endpoint retrieves all downloads.

### HTTP Request

`GET htts://sug.rocks/api/dl.json`

<aside class="notice">Files that contains two episodes in one have an underscore between episodes number. Like for episode 1 & 2: `1_2`.</aside>
<aside class="notice">`url`, `marebucks`, `dailymotion` and `torrent` can be "null" if not available.</aside>
