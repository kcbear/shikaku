# shikaku
Visualisation for timeline, tread, stock, FX
Designed to run in S3, all the JS dependencies are from CDN


1. use dynatable to render JSON data
https://datatables.net/manual/data/index#Processing-modes

2. use tradingview for the quick stock/news data chart rendering
https://www.tradingview.com/widget/advanced-chart/

3. use Alphavantage as the data provider for VIX data time series
Awesome, easy API for stock data, many extension points for Alphavantage
https://www.alphavantage.co/documentation/

4. embed Google trend for interest search

5. Chart render is using canvas js
https://canvasjs.com/html5-javascript-area-chart/