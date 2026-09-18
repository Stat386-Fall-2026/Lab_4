# Lab 4 data

`talks.csv` contains 794 General Conference talks from 2010 through 2020.
Each row represents one talk. It has the following columns:

| Variable | Description |
|---|---|
| `talk_name` | Title of the talk |
| `speaker` | Name of the speaker |
| `session` | Conference session in which the talk was given |
| `date` | Date of the talk |
| `month` | Conference month |
| `year` | Conference year |
| `conference` | Conference name, such as `April 2020` |
| `role` | Speaker's leadership role at the time of the conference |
| `speaker_order` | Speaker's order within the session |
| `num_words` | Number of words in the talk |
| `runtime` | Recorded runtime of the talk |
| `talk_number` | Talk order within the session |
| `link` | Link to the talk |
| `kicker` | Short summary of the talk |
| `text` | Full transcript of the talk |

The `text` column has no missing values. The `runtime` column has 131 missing
values, and the `kicker` column has 2 missing values. All other columns are
complete in this file.
