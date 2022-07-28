# Faces From Places website (WIP)

## Updating questions

To update the questions (aka ice breakers, aka drop ins):

1. Download a CSV file from Google Sheets
2. Override `data.csv` with the new file
3. If the column names are updated in the `.csv` file, please also update the keys in `index.html`. They should match below.

The Google Sheet (and CSV file) should have two columns:

* `Question`
* `Categories (yes/no, casual, deep)`