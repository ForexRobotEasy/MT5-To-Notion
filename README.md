# MT5 To Notion

MT5 To Notion is a Forex trading robot developed by the Forex Robot Easy Team. This program allows traders to export trade-related data from MetaTrader 5 (MT5) to Notion, a popular productivity and collaboration tool. By automating the export process, traders can streamline their trade analysis and reporting.

## How It Works

The code provided in this repository demonstrates how to connect to MT5 and Notion using the respective connectors. The `OnInit()` function initializes the connections to both platforms, while the `OnDeinit()` function disconnects from them. The `OnTick()` function is triggered on each tick, and it calls the `ExportTradeData()` function to export trade-related data.

The `ExportTradeData()` function performs the following tasks:

1. Retrieves the running trades from MT5 using the `GetRunningTrades()` function.
2. Exports the running trades to Notion using the `ExportRunningTrades()` function.
3. Retrieves the pending orders from MT5 using the `GetPendingOrders()` function.
4. Exports the pending orders to Notion using the `ExportPendingOrders()` function.
5. Retrieves the trades from the last day from MT5 using the `GetTradesLastDay()` function.
6. Exports the trades from the last day to Notion using the `ExportTradesLastDay()` function.
7. Retrieves the trades from the last week from MT5 using the `GetTradesLastWeek()` function.
8. Exports the trades from the last week to Notion using the `ExportTradesLastWeek()` function.
9. Retrieves the trades from the last month from MT5 using the `GetTradesLastMonth()` function.
10. Exports the trades from the last month to Notion using the `ExportTradesLastMonth()` function.
11. Retrieves the trades from a custom time range from MT5 using the `GetTradesCustomRange()` function.
12. Exports the trades from the custom time range to Notion using the `ExportTradesCustomRange()` function.
13. Exports selective field data to Notion using the `ExportSelectiveFieldData()` function.
14. Enables automatic updates between MT5 and Notion using the `EnableAutomaticUpdates()` function.
15. Prints a success message.

The `OnStart()` function is executed when the program starts and calls the `ExportTradeData()` function to export trade-related data.

## Product Description

MT5 To Notion is a powerful tool designed to streamline the export of trade-related data from MT5 to Notion. By automating this process, traders can save time and effort in analyzing and reporting their trades. This product allows traders to:

- Export running trades, pending orders, and trade history from MT5 to Notion.
- Customize the time range for exporting trade data.
- Selectively export specific fields of trade data.
- Enable automatic updates between MT5 and Notion for real-time trade data synchronization.

Please note that ForexRobotEasy is not the official developer of this product. We provide this sample code as an example of how the product can work. To find the official developer of this product, please refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/mt5-to-notion-review-streamline-forex-trades-export/).
