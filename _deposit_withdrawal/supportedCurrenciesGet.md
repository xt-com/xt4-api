---
title: Get the supported currencies for deposit or withdrawal
position_number: 1
type: get
description: /openapi/public/support/currency
parameters:
    
        
content_markdown:
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
                  "rc": 0,
                  "mc": "string",
                  "ma": [
                    {}
                  ],
                  "result": [
                    {
                        "currency": "string",
                        "supportChains": [
                            {
                                "chain": "Bitcon",     //Supported Transfer Networks
                                "depositEnabled": true,     //deposit is supported or not
                                "withdrawEnabled": true     //withdraw is supported or not
                            }
                            {
                                "chain": "FIO",
                                "depositEnabled": true,
                                "withdrawEnabled": true
                            }
                        ]           
                    },
                    {
                        "currency": "string",
                        "supportChains": [
                            {
                                "chain": "Ethereum",
                                "depositEnabled": true,
                                "withdrawEnabled": true
                            }
                        ]
                    }
                  ]
                }
        title: Response
        language: json
---