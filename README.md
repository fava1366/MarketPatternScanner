# Market Pattern Scanner Android v1.4
Chart rendering hotfix: always draw received raw 1-minute OHLC rows, regardless of aggregation/pattern availability. Pattern calculation remains separate using closed M3/M5/M15 bars. If the canvas is blank, the API returned no valid OHLC rows or the installed APK is not this build.
Uses Twelve Data API via native Android HTTPS bridge. No MT5 connection, no trade execution.
Not device-tested; confirm provider plan/API response with user's actual key.
