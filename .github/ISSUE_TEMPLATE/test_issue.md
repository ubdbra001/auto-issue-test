---
title: New financial year: {{ date | date('D MMM Y') }} - update handbook checklist
assignees: ubdbra001
---

- [ ] Create `{{ date | date('YYYY') }}/{{ date| date('add', 1, 'year') | date('YY') }}`  directory in [HoRSE/Finances](https://drive.google.com/drive/folders/1MQ2r4EvyutX9kQOJ8BFQAq0rTzS9ERJK)
- [ ] In this new directory create a new spreadsheet named `FY {{ date | date('YY') }}/{{ date| date('add', 1, 'year') | date('YY') }}`
- [ ] Update `expenses.qmd` to use the new urls for directory and spreadsheet created in the previous 2 steps
