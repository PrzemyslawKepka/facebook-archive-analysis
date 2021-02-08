# Overview

Facebook gives the user ability to download a copy of all his activities, including messages, list of friends or liked pages, and data may be extracted in JSON or HTML format. This project allows to ingest the extracted data (currently messages and list of friends) in JSON format, and from even hundreds of source files appriopriate tables are created, and they are stored in pandas dataframes and also database is created with usage of `SQLite`, allowing to analyze the data not only in Python, but also using database interface.

Screenshots below are presenting created database opened with `DB Browser for SQLite`, and code for data extraction and example analysis with pandas and SQL is shown in Jupyter file.

<p float="left">
  <img src="https://github.com/PrzemyslawKepka/facebook_archive_analysis/blob/main/db_sqlite_data.PNG" width="500" />
  <img src="https://github.com/PrzemyslawKepka/facebook_archive_analysis/blob/main/db_sqlite_structure.PNG" width="500" /> 
</p>
