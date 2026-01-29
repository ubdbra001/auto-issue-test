---
title: "New financial year: {{ date | date('MMM Y') }} - update handbook checklist"
assignees: ubdbra001
---

- [ ] Create a directory `{{ date | date('Y') }}/{{ date | date('add', 1, 'Y') | date('YY') }}` in [HoRSE/Finances](https://drive.google.com/drive/folders/1MQ2r4EvyutX9kQOJ8BFQAq0rTzS9ERJK)
- [ ] In this new directory create a new spreadsheet from the `FY template` file, called `FY {{ date | date('YY') }}/{{ date | date('add', 1, 'Y') | date('YY') }}`
- [ ] Update `expenses.qmd` to use the new urls for directory and spreadsheet created in the previous 2 steps
