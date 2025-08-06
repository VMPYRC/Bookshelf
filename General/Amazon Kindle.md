---
created: 2025-07-20
modified: 2025-07-20
description: Resources for Amazon Kindle
aliases:
  - Kindle
tags:
  - Notes
  - eReader
---

# Send to Kindle

- https://www.amazon.com/sendtokindle

# Free Amazon Kindle eBooks

Quick Link:

```
https://www.amazon.com/
s?k=+mystery+-horror+-romance
&i=digital-text
&rh=n%3A154606011%2Cp_36%3A0-0
&s=price-desc-rank
```

Let's break this down:

| Parameters              | Meaning                                                                                                                                                              |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| https://www.amazon.com/ | - Base URL                                                                                                                                                           |
| s?k=                    | - Initiate a search                                                                                                                                                  |
| +mystery                | - ✅ Mystery<br>- Show me all mystery<br>- Plus (+) is yes                                                                                                           |
| +-horror<br>+-romance   | - ❌ Horror<br>- ❌ Romance<br>- DO NOT show me any Horror or Romance<br>- Plus Minus (+-) is no                                                                     |
| &i=digital-text         | - Restricts the search results to Kindle eBooks                                                                                                                      |
| &rh=                    | - Refinement filter (?)                                                                                                                                              |
| n%3A154606011           | - Kindle Store Category                                                                                                                                              |
| %2Cp_36%3A0-0           | - Price filter: Free only<br>- 0-0 means books that cost $0 to $0                                                                                                    |
| &s=price-desc-rank      | - Sorts the results by price, highest to lowest<br>- (This lets me know that the entire link is working since the highest priced book (first result) would be $0.00) |
