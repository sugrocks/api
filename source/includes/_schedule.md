# Schedule

```json
{
  "cn": [
    {
      "date": "March 03",
      "id": 2065557,
      "time": "7:00 PM",
      "timestamp": 1488585600,
      "title": "Tiger Philanthropist"
    },
    {
      "date": "March 05",
      "id": 2083879,
      "time": "4:00 PM",
      "timestamp": 1488747600,
      "title": "New Crystal Gems /That Will Be All"
    }
  ],
  "zap": [
    {
      "date": "3/23/2017",
      "episode": "S04E20",
      "id": 322327565454,
      "synopsis": null,
      "title": "Lion 4: Alternate Ending"
    },
    {
      "date": "3/10/2017",
      "episode": "S04E19",
      "id": 300907630993,
      "synopsis": null,
      "title": "Room for Ruby"
    }
  ]
}
```

This endpoint retrieves a copy of Cartoon Network's and Screener's (Zap2It) schedule for Steven Universe.

### HTTP Request

`GET https://api.sug.rocks/schedule.json`

<aside class="notice">This endpoint is using the American Eastern timezone (EST, -0500). Use the added `timestamp` value to convert to your own (local) timezone if needed.</aside>
