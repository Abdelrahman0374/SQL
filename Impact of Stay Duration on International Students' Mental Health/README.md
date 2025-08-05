# Impact of Stay Duration on International Students' Mental Health

## 📌 Project Overview
This SQL analysis explores how the length of stay (`stay`) affects mental health diagnostic scores of international students. Using depression (PHQ-9), social connectedness (SCS), and acculturative stress (ASISS) metrics, we quantify the relationship between stay duration and psychological well-being.

## 🔍 Business Question
> "How does the length of stay impact average mental health diagnostic scores of international students?"

## 📊 Analysis Requirements
1. Filter to international students (`inter_dom = 'Inter'`)
2. Calculate for each stay duration:
   - `count_int`: Number of international students
   - `average_phq`: Average PHQ-9 score (todep) rounded to 2 decimals
   - `average_scs`: Average SCS score (tosc) rounded to 2 decimals
   - `average_as`: Average ASISS score (toas) rounded to 2 decimals
3. Return 9 rows sorted by `stay` descending
