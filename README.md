# The Library

I've created this project because I like using [Notion](https://notion.so) to keep track of academic papers I read, but hate adding metadata to each paper manually. This project aims at automatically adding metadata to papers using the [Semantic Scholar API](https://api.semanticscholar.org/).

This project is designed to be run as a GitHub Action, but can also be run locally. The action has access to a Notion API token, which is used to update the database, and optionally requires a free Semantic Scholar API token (useful if downloading a large amount of metadata all at once, since the APIs are capped at 100 requests / 5 minutes).
