# Hack4Her Starter Review Data

This folder contains participant-ready synthetic review CSV files.

Record count per scenario: `1000`

All reviews, properties, labels, and coordinates are synthetic mock data for hackathon prototyping. They are not Booking.com customer reviews and must not be interpreted as real safety ratings for any location.

## Scenarios

- `balanced`
- `safety_heavy`
- `location_focus`
- `host_focus`
- `stay_focus`
- `mostly_positive`

## How To Use

Pick one CSV file to start with:

- `balanced`: general prototype dataset.
- `safety_heavy`: stress test for safety-detection ideas.
- `location_focus`: map, neighborhood, route, or transit ideas.
- `host_focus`: host conduct, check-in, or support ideas.
- `stay_focus`: lock, privacy, room, or on-property safety ideas.
- `mostly_positive`: sparse-signal dataset for harder detection.
- `random`: surprise-test dataset, if present.

The main `_public.csv` files are participant files, so helper answer columns such as `is_safety_related`, `safety_category`, and `labels` are not included.

Each scenario also includes a `_golden_10pct.csv` file with labels for 10% of the rows. Use that smaller golden sample for validation, scoring, demos, or model checks without revealing labels for the full dataset.

Important columns:

- `review_text`, `review_title`, `language`, `rating`
- `city`, `country`, `latitude`, `longitude`, `area_type`
- `traveler_type`, `reviewer_country`, `nights`, `review_date`, `stay_month`

To regenerate this starter pack from the repo root:

```bash
python3 scripts/generate_mock_reviews.py --starter-pack --records 1000 --output-dir uvx hack4her-review-data starter --records 1000
```
