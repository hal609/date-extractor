# date_extractor

A Python module to fuzzy extract dates from a corpus of text.

## Installation

```
pip install date_extractor
```

## Usage

```python
from date_extractor import find_dates

print(find_dates("A thing happened on Jan 1st 2012 and Jan 2nd 2012, and also january 15th at 12am in 2018."))

# Output
['2012-01-1st', '2012-01-2nd', '2018-01-15th 12am']
```