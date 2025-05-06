# generate_monthly_billing
This project calculates prorated monthly billing for items based on their active dates, quantities, and rates.

## 🧩 Features

- Calculates billing based on active days in a selected month.
- Groups items by `item_code`, `rate`, and billing period.
- Computes total revenue from all line items.
- Skips invalid entries with error logging.

## 🛠️ How It Works

1. Parse dates and determine monthly range.
2. For each item:
   - Check if active during the target month.
   - Calculate prorated amount.
3. Group by unique billing keys.
4. Output structured bill and total revenue.
