# Exporting-Chrome-Browser-History-to-Wazuh-Windows-
This script safely copies Chrome's locked SQLite History DB, exports only new events (incremental), and writes them as NDJSON files that Wazuh ingests. It supports current user or all users (SYSTEM runs), converts Chrome timestamps correctly, and survives locks/errors with clear debug logging.
# Medium article complete url
https://medium.com/@shehryartalat41/exporting-chrome-browser-history-to-wazuh-windows-a-fast-incremental-ndjson-pipeline-785817ef85df
