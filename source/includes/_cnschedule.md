# CN's Schedule

```json
{
  "2017-07-06": {
    "source": "Cartoon Network",
    "schedule": [
      {
        "date": "2017-07-06",
        "time": "6:00 am",
        "timestamp": 1499335200,
        "timestamp_end": 1499337000,
        "show": "Amazing World of Gumball",
        "title": "Friend /Saint ",
        "slots": 2
      },
      {
        "date": "2017-07-06",
        "time": "6:30 am",
        "timestamp": 1499337000,
        "timestamp_end": 1499338800,
        "show": "Amazing World of Gumball",
        "title": "Oracle /Safety ",
        "slots": 2
      }
    ]
  },
  "2017-07-17": {
    "source": "Zap2it",
    "schedule": [
      {
        "date": "2017-07-17",
        "time": "6:00 am",
        "timestamp": 1500289200,
        "timestamp_end": 1500291000,
        "show": "Amazing World of Gumball",
        "title": "The Coach; The Joy",
        "slots": 2
      },
      {
        "date": "2017-07-17",
        "time": "6:30 am",
        "timestamp": 1500291000,
        "timestamp_end": 1500292800,
        "show": "Amazing World of Gumball",
        "title": "The Kids; The Fan",
        "slots": 2
      }
    ]
  },
  "_": {
    "generated": 1499619654
  }
}
```

This endpoint retrieves a copy of Cartoon Network's schedule from various sources ("Cartoon Network" and "Zap2it"). It usually goes from 3 days back to 13 days ahead.

**Details of a `schedule` element:**

- `date` and `time` are straightforward
- `timestamp` is when the block starts
- `timestamp_end` is when the block ends
- `show` is the name of the show (might also be `SPECIAL` or `MOVIE`)
- `title` is the episode(s)/movie/block title (might be `null`)
- `slots` is the length of the block. A single slot is usually 15 minutes

### HTTP Request

`GET https://api.sug.rocks/cnschedule.json`

<aside class="notice">This endpoint is using the American Eastern timezone (EST, -0500). Use the added `timestamp` value to convert to your own (local) timezone if needed.</aside>
