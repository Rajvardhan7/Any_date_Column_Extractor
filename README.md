# Any_date_Column_Extractor
Concept of NLP and mattern has been leveraged

FUNCTION EXPLAINATION

To make a robust fuction that can deal with any date format, use of both NLP approach(like text recognition, Machine Translation) as well as pattern matching(i.e. regular expressions) are to be leveraged which is on what lexnlp is built upon

2 important points about get_date method of lexnlp module:

It can detect any human readable date format! and returns an empty list if no date format is encountered.

It converts any date format into YYYY/MM/DD format thus makes subs. between 2 date objects possible.

function(DaysBtDates) parameters:

data : numpy ndarray/pandas dataframe

impute : takes imputation with mode into account if set True.
