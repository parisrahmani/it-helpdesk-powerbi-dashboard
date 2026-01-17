# Data Source Information

## Dataset Origin
The dataset was created as part of an academic study involving a help desk team at an international software company. It represents aggregated issue records extracted from a PostgreSQL database.
[DataSet](https://data.mendeley.com/datasets/btm76zndnt/2)) - issues.csv

## Time Coverage
The dataset includes issue records created between 2007 and 2023. However, consistent and reliable documentation practices began in 2016.

## Data Masking
To protect privacy, several fields were anonymized, including project identifiers, reporters, and assignees. Masking preserves structural relationships while removing identifiable information.

## Legacy Data Considerations
Issues created before 2016 often lack key operational fields such as priority and resolution timestamps. These records were flagged as legacy data and excluded from performance analysis to ensure metric reliability.
