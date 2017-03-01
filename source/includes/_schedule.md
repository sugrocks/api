# Schedule

```json
[
  {
    "date": "March 03",
    "id": 2065557,
    "time": "7:00 PM",
    "timestamp": 1488585600,
    "title": "Tiger Philanthropist"
  },
  {
    "date": "March 10",
    "id": 2083881,
    "time": "7:00 PM",
    "timestamp": 1489190400,
    "title": "Room for Ruby"
  }
]
```

This endpoint retrieves a copy of Cartoon Network's schedule for Steven Universe.

- Not included: TV ratings (like `[TV-PG]`)
- Added: timestamp

### HTTP Request

`GET https://api.sug.rocks/schedule.json`

<aside class="notice">This endpoint is using the American Eastern timezone (EST, -0500). Use the epoch `timestamp` to convert to your own (local) timezone if needed.</aside>
