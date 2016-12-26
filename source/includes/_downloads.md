# Downloads

```json
{
  "individual": [
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "1",
      "id": 1,
      "marebucks": "https://marebucks.com/sun/1",
      "season": "1",
      "title": "Gem Glow",
      "torrent": null,
      "url": "https://example.com/mega/01x01.mp4"
    },
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "2",
      "id": 2,
      "marebucks": "https://marebucks.com/sun/2",
      "season": "1",
      "title": "Laser Light Cannon",
      "torrent": null,
      "url": "https://example.com/mega/01x02.mp4"
    },
  ],
  "itunes": [
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "1_2",
      "id": 1,
      "marebucks": "https://marebucks.com/sun/1",
      "season": "1",
      "title": "Gem Glow & Laser Light Cannon",
      "torrent": "https://example.com/torrents/01x01_02.mkv.torrent",
      "url": "https://example.com/01x01_02.mkv"
    },
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "3_4",
      "id": 2,
      "marebucks": "https://marebucks.com/sun/3",
      "season": "1",
      "title": "Cheeseburger Backpack & Together Breakfast",
      "torrent": "https://example.com/torrents/01x03_04.mkv.torrent",
      "url": "https://example.com/01x03_04.mkv"
    },
  ],
  "preair": [
    {
      "dailymotion": "https://dailymotion.com/",
      "date": 1473502695,
      "episode": 1,
      "id": 1,
      "marebucks": "https://marebucks.com/sun/",
      "season": 1,
      "title": "episode title",
      "torrent": null,
      "url": "https://example.com/preair/ep.mkv"
    }
  ]
}
```

This endpoint retrieves all downloads.

### HTTP Request

`GET https://api.sug.rocks/dl.json`

<aside class="notice">Files that contains two episodes in one have an underscore between episodes number. Like for episode 1 & 2: `1_2`.</aside>
<aside class="notice">`url`, `marebucks`, `dailymotion` and `torrent` can be "null" if not available.</aside>
