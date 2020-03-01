# SI-649-final-project
A repo of code for the SI 549 final project, including EDA.

### Cleaned files included:

##### steam_wide.csv:
Contains the number of users as an integer (average of the range given in data/steam.csv; see below).
Also merged the text descriptions of each game into this file for any desired text mining. One row
per game.

##### steam_long.csv:
Contains separate entries for each genre of a game, so that each game with multiple genres
has multiple rows.

### Files and descriptions from the data repository (you can get the data repo [here](https://drive.google.com/drive/folders/1y7pH1qMRDwj-DrJkfSdeD9foiygzJj_y?usp=sharing)):

##### steam.csv:
  Main file. Contains lots of information, organized by video game title.
  "appid" field is the primary key between this and other data.

##### steam_description.csv:
  Contains the textual descriptions of the games in various formats (long, short, etc).
  Could be useful to do some simple text mining.

##### steamspy_tag_data.csv:
  Contains the number of tags that users have applied to each video game title. Useful for
  categorization by user-input.

##### Other steam files are less likely to be useful.
