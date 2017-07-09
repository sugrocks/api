# Downloads

```json
{
  "_": {
    "generated": 1496501844
  },
  "comics": [
    {
      "category": "Books",
      "cbr": "https://example.com/SUG-CBR-BOOK-GTTCG.cbr",
      "cbz": "https://example.com/SUG-CBZ-BOOK-GTTCG.cbz",
      "date": 1490369885,
      "epub": "https://example.com/SUG-EPUB-BOOK-GTTCG.epub",
      "id": "BOOK-GTTCG",
      "pdf": "https://example.com/SUG-PDF-BOOK-GTTCG.pdf",
      "title": "Guide to the Crystal Gems"
    },
    {
      "category": "Main Comics (2014-15)",
      "cbr": "https://example.com/SUG-CBR-COMIC01.cbr",
      "cbz": "https://example.com/SUG-CBZ-COMIC01.cbz",
      "date": 1490369885,
      "epub": "https://example.com/SUG-EPUB-COMIC01.epub",
      "id": "COMIC01",
      "pdf": "https://example.com/SUG-PDF-COMIC01.pdf",
      "title": "Issue 01"
    },
  ],
  "individual": [
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "01",
      "id": 101,
      "marebucks": "https://marebucks.com/sun/1",
      "season": "01",
      "title": "Gem Glow",
      "torrent": null,
      "url": "https://example.com/mega/01x01.mp4"
    },
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "02",
      "id": 102,
      "marebucks": "https://marebucks.com/sun/2",
      "season": "01",
      "title": "Laser Light Cannon",
      "torrent": null,
      "url": "https://example.com/mega/01x02.mp4"
    }
  ],
  "itunes": [
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "01_02",
      "id": 10102,
      "marebucks": "https://marebucks.com/sun/1",
      "season": "01",
      "title": "Gem Glow & Laser Light Cannon",
      "torrent": "https://example.com/torrents/01x01_02.mkv.torrent",
      "url": "https://example.com/01x01_02.mkv"
    },
    {
      "dailymotion": null,
      "date": 1473502695,
      "episode": "03_04",
      "id": 10304,
      "marebucks": "https://marebucks.com/sun/3",
      "season": "01",
      "title": "Cheeseburger Backpack & Together Breakfast",
      "torrent": "https://example.com/torrents/01x03_04.mkv.torrent",
      "url": "https://example.com/01x03_04.mkv"
    }
  ],
  "preair": [
    {
      "dailymotion": "https://dailymotion.com/video/x5lts7g",
      "date": 1473502695,
      "episode": "01",
      "id": 501,
      "marebucks": "https://marebucks.com/sun/127",
      "season": "05",
      "title": "Stuck Together",
      "torrent": null,
      "url": "https://example.com/preair/ep.mkv"
    }
  ]
}
```

This endpoint retrieves all downloads.

**`individual`, `itunes` and `preair` share the same structure, but `comics` is totally different.**

### HTTP Request

`GET https://api.sug.rocks/dl.json`

<aside class="notice">Files that contains two episodes in one have an underscore between episodes number. Like for episode 1 & 2: `01_02`.</aside>

<aside class="notice">For episodes: `url`, `marebucks`, `dailymotion` and `torrent` can be "null" if not available.<br>
The same goes with comics and books: `cbr`, `cbz`, `epub` and `pdf` can be "null" if not available.</aside>
