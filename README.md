# Video Games Sales Analysis (Excel)

An analysis of global video game sales, built entirely in Microsoft Excel using PivotTables, formulas and charts.

> **Note:** This is an early project from my HNG Internship April 2026.
> I have kept it unchanged to show my starting point as I transition into data analysis. See "Limitations" for what I would do differently.

## Dataset
- **Source:** Given by HNG
- **Size:** 64,016 rows and 14 columns
- **Fields:** title, console, genre, publisher, developer, critic score, total sales, regional sales (North America, Japan, PAL/Europe, Other), release date, last update

## Questions
1. Which genres and publishers lead in total global sales?
2. What are the sales patterns across regions?
3. How do average critic scores differ by genre?

## Tools and Techniques
- Microsoft Excel: PivotTables, SUM formulas, charts
- Data review and preparation in a raw sheet and a working sheet

## Key Findings
- Sports, Action, and Shooter are the top genres, together making up about half of recorded global sales.
- North America accounts for about 51% of regional sales, followed by PAL/Europe (29%), Japan (10%), and Other (10%).
- Activision is the top publisher by total sales, ahead of Electronic Arts and EA Sports.
- Genres at the bottom of the critic score ranking include Board Game and Party games.

## Limitations (and what I'd do differently)
- About 70% of rows (45,094 of 64,016) have no total sales figure, and only 6,678 have a critic score, so the findings cover a subset of games.
- Some genres in the critic score chart (e.g., Sandbox, Board Game) are based on one or two games, so their averages are not reliable.
- My original conclusion that critic scores "don't matter" for sales was not tested. A quick check suggests a weak-to-moderate positive relationship, which I would explore properly next time.
- Nintendo ranks low, likely because many of its titles have no sales data in this dataset.
- Next time I would document my cleaning steps and add a genre-by-region breakdown.

## Files
- `Video_Games_Sales_Rukky.xlsx`: raw data, working data, and all analysis sheets
- `VIDEO_GAMES_ANALYSIS_Rukky.pptx` / `.pdf`: presentation of findings
- `images/`: chart exports

## Author
Rukky | https://www.linkedin.com/in/rhukhi | rukkyujara@gmail.com
