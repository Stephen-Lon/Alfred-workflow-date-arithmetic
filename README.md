# Alfred-workflow-date-arithmetic
Calculate day offsets and days between given dates

# Introduction

This workflow allows you to do two things. You can either calculate:
- the offset from a specified date calculated in days (for example, plus 24 days or minus 320 days); or
- the number of days between two given dates.

If you regularly use one of those options more than the other you can set the default option in the User Configuration. The result will enable you simply to dismiss the relevant dialog by pressing ⏎. 

# Important note

In the configuration of this workflow you can choose to use the European date format (dd/mm/yyyy)—which is the default—or, by un-checking the checkbox, choose to use the US date format (mm/dd/yyyy).

---

**For this workflow to work properly these must match:**

- the date format you choose in configuration of the workflow; and
- the format of your computer's date in `System Settings > Language & Region > Date format`.

**The workflow will not work properly if those settings do not match.**

---

# Usage: calculating the offset from a given date

When prompted type the date—following the format set in the User Configuration—and press ⏎. Choose `Calculate offset` from the dialog which is then displayed and type the offset (i.e., plus or minus the number of days) you want followed by ⏎.

**Note**: You simply have to type -5, +230, -4034, etc. *Don't use any spaces, don't use commas within numbers and don't use any characters (like `d`) after the numbers*.

# Usage: calculating the days between two dates

Start the workflow exactly as before: when prompted type the date—following the format set in the User Configuration—and press ⏎. Choose `Calculate days between 2 dates` from the dialog which is then displayed and then type the second date (again following the format set in the User Configuration) followed by ⏎.

**Note**: It does not matter if the first date is later than the second: the workflow will take account of that.
