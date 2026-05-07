# AI Tool Directory Monitor

The **AI Tool Directory Monitor Scraper** scrapes directories like Futurepedia to identify newly listed AI tools and monitor the latest additions to AI ecosystems.

## Features:
1. **Daily Updates**: Scrapes directories daily to find newly added tools.
2. **Filters by Date**: Collects only tools added after a specified date.
3. **Metadata Collection**: Gathers tool name, description, category, pricing, and source URL.
4. **Customizable Limits**: Option to limit the number of tools scraped per run.

## Inputs:
1. **directoryUrls**: URLs of AI directories to scrape (e.g., Futurepedia).
2. **dateFilter**: Start date for filtering new tools (format: YYYY-MM-DD).
3. **maxToolsPerRun**: Maximum number of tools to scrape per session.

## Outputs:
- **Tool Name**: Name of the AI tool.
- **Description**: Brief summary of what the tool does.
- **Category**: The tool's category (e.g., productivity, design).
- **Pricing**: The pricing model (e.g., free, freemium, paid).
- **Source URL**: Link to the tool's page.
- **Date Added**: Date the tool was added to the directory.

## Use Cases:
- **Daily Monitoring**: Highlight the latest AI tools added to the ecosystem.
- **Trend Analysis**: Track which categories or pricing models are trending.
- **Community Discovery**: Help AI researchers and developers find tools faster.

---
