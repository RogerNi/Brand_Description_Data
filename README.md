# Brand_Description_Data

## Introduction
1475 brands with their descriptions from different sources are included in the file.

## Standardized Data
### Raw Data (Corpus)
#### Contents
File|Description
---|---
`./brands.json`|Data

#### Format
All files are in `json` format. Here is a sample:
```
[
    {
        "Brand_Name": "Python",
        "Category": "Programming Language",
        "Description": [
            {
                "Source": "Wiki",
                "Content": "Python is an interpreted, high-level, general-purpose programming language."
            },
            {
                "Source": "https://www.python.org/",
                "Content": "Python is a programming language that lets you work quickly and integrate systems more effectively."
            },

            ...
            ...
            ...

        ]
    },

    ...
    ...
    ...

]

```

## Issues
+ The context from Wikipedia may have problems with the format that some sentences are splitted by `line break` but not `Whitespace Character`.
+ Some brands are unfortunate to have no context crawled.
