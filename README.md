sleep-debt-and-screen-time-late-night-phone-habits# Sleep Debt and Screen Time - Late Night Phone Habits

**Health Data Analyst Project | R | Remote**
**Dataset:** Samar Talwar | Kaggle | 8,500 records × 18 variables
**Kaggle Path:** `/kaggle/input/sleep-debt-and-screen-time-late-night-phone-habits/`

### Business Problem
How do late-night phone habits create sleep debt and affect next-day health?

### Tools & Data
- R, dplyr, ggplot2, readr
- 18 vars: bedtime_phone_minutes, sleep_latency_min, total_sleep_hours, deep_sleep_pct, rem_sleep_pct, blue_light_filter_active, primary_bedtime_app, sleep_debt_category, next_day_fatigue_score + demographics

### Analysis
```r
df <- read_csv("/kaggle/input/sleep-debt-and-screen-time-late-night-phone-habits/sleep_debt_and_screen_time.csv")
