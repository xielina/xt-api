---
title: Get unrealized total profit sharing
position_number: 16
type: get
description: /v4/balance/copy-trade/share-profit/expected
parameters:
    
content_markdown: >-
    #### **Limit Flow Rules**

    1/s/apikey
left_code_blocks:
    -
        code_block:
        title: Java
        language: java
    -
        code_block:
        title: Python
        language: python
right_code_blocks:
    -
        code_block: |-
                   {
                     "ma": [
                       {}
                     ],
                     "mc": "string",
                     "rc": 0,
                     "result": 0    //unrealized profit sharing amount
                   }
        title: Response
        language: json
---