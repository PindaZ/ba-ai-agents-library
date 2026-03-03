# Market Intelligence Scraper Skill

**Category:** Strategic Advisory
**Goal:** Continuously monitor the web for competitor AI announcements and industry shifts.

## Prerequisites
- List of top 5 competitors.
- Target industry keywords (e.g., "Generative AI in Healthcare").

## Required Tools/Integrations
- `web_fetch` (for news sites/press releases)
- `google_web_search`

## Execution Workflow
1. **Query Generation:** Generate search strings combining competitor names with AI keywords (e.g., "Competitor X machine learning release").
2. **Data Scraping:** Fetch the top 10 recent news articles or press releases.
3. **Summarization:** Extract the core feature, launch date, and underlying technology (if mentioned) from each article.
4. **Impact Analysis:** Determine if the competitor move is a "High," "Medium," or "Low" threat to current strategy.
5. **Briefing Creation:** Compile a weekly/monthly intelligence briefing.

## Expected Output
An "Intelligence Briefing" document summarizing competitor moves and suggested countermeasures.
