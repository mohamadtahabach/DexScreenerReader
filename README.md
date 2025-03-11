# DexScreenerReader
DexScreenerReader is a Java-based crypto data monitoring tool that reads RSI (Relative Strength Index) values from a file, evaluates conditions, and sends alerts via Discord. It automates the execution of a UiPath bot to process cryptocurrency data and notify users when RSI crosses predefined thresholds.

1️. Reads Crypto Data: Loads data from cryptoData_{name}.txt, extracting key financial indicators.

2️. Executes UiPath Bot: Runs the latest version of a UiPath package to update crypto data.

3️. Analyzes RSI Values: Checks if RSI crosses the 35 or 65 thresholds.

4️. Sends Discord Alerts: Uses JDA (Java Discord API) to send messages to a Discord channel.

5️. Manages Files Efficiently: Deletes old versions and updates files dynamically.
