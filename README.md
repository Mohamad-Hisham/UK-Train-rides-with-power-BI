# UK Train Rides with Power BI

A Power BI analytics project exploring UK rail ticket sales, journey performance, and customer behaviour.

## Repository contents

- `UK Train Rides Final project.pbix` — Main Power BI report/dashboard file.
- `railway.csv` — Primary transaction-level dataset (31,653 rows, 18 columns).
- `railway.xlsx` — Spreadsheet version of the railway dataset.
- `railway_data_dictionary.csv` — Field definitions for the railway dataset.
- `Uk Train Powerbi Documentation.docx` — Project documentation.

## Dataset overview

The dataset captures ticket purchases and journey outcomes, including:

- Purchase details (date/time, channel, payment method)
- Ticket details (class, type, railcard, price)
- Route details (departure and arrival stations, planned times)
- Performance details (actual arrival time, delay status, delay reason)
- Customer service outcome (`Refund Request`)

### Core fields

`Transaction ID`, `Date of Purchase`, `Time of Purchase`, `Purchase Type`, `Payment Method`, `Railcard`, `Ticket Class`, `Ticket Type`, `Price`, `Departure Station`, `Arrival Destination`, `Date of Journey`, `Departure Time`, `Arrival Time`, `Actual Arrival Time`, `Journey Status`, `Reason for Delay`, `Refund Request`.

## How to use this project

### 1) Open the report

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open `UK Train Rides Final project.pbix`.

### 2) Refresh data (if needed)

If the report prompts for data source paths:

1. Go to **Transform data** → **Data source settings**.
2. Point queries to `railway.csv` (or `railway.xlsx`) in your local clone.
3. Click **Refresh**.

### 3) Explore analysis

Use report pages/filters to analyze:

- Revenue and ticket price trends
- Route demand by station pairs
- Delay rates and top delay causes
- On-time performance by ticket or purchase segment
- Refund-request patterns

## Suggested KPI ideas

If you want to extend the report, consider adding:

- Total revenue
- Average ticket price
- Delay rate (%)
- On-time arrival rate (%)
- Refund request rate (%)
- Top routes by volume and value

## Notes

- Date/time columns may require regional formatting adjustments depending on locale.
- `Reason for Delay` is blank for on-time journeys.
- Keep source files in consistent paths to avoid broken Power BI query links.

## License

No license is currently specified in this repository.
