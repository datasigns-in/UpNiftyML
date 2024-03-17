# UpNiftyML

**Upstox API: ** The Upstox API comprises a suite of RESTful APIs designed to supply the necessary data for constructing a comprehensive investment and trading platform. These APIs enable real-time order execution, user portfolio management, live market data streaming via Websockets, and more, all presented in an easily comprehensible API collection.

All requests are transmitted securely via HTTPS, and they are formatted with the 'application/json' content type. All responses are provided in JSON format, except for the instrumental API, which yields a CSV response..

To utilize these APIs, creating an application within the Developer Console is imperative, generating both an apiKey and apiSecret.You need to specify a redirect URL, which will be invoked following the login process with the auth code. Optionally, you can provide a Postback URL where you can receive live updates on order statuses.

https://upstox.com/developer/api-documentation/get-historical-candle-data

API GET Request: /historical-candle/:instrument_key/:interval/:to_date/:from_date

1. Download Complete Instrument List: https://assets.upstox.com/market-quote/instruments/exchange/complete.csv.gz
2. Filter Selected Instruments
3. Upload on google drive folder
4. Mount Google drive to Colab sheet
5. Map path of Gdrive folder to access Instrument List
6. Map path of Gdrive to download data
7. execute
8. CSV and JSON files are avilable directly in Gdrive
9. Nifty50 and NVIX are symboles used for Nifty 50 and India Vix in these sheets.


