---
slug: /poscreators/middleware-doc/montenegro/reference-tables/ftreceiptcase
title: 'Type of receipt: ftReceiptCase'
---

# Type of Receipt: ftReceiptCase

The `ftReceiptCase` indicates the receipt type and defines how the fiskaltrust.SecurityMechanism should process it following Montenegrin law.

For Montenegro (ME), the country code is `0x4d45`. Thus, the value of an unknown `ftReceiptCase` in Montenegro is `0x4d45000000000000`.

| **Value**            | **Description**                             | **Version** |
|----------------------|---------------------------------------------|-------------|
|`0x4d45000000000000`  |**Unknown type for country-code "ME"**       |-------------|
|`0x4d45000000000001`  |**Pos-receipt**                              |-------------|
|`0x4d45000000000002`  |**Zero-receipt**                             |-------------|
|`0x4d45000000000003`  |**Initial operation receipt / start-receipt**|-------------|
|`0x4d45000000000004`  |**Out of operation receipt / stop-receipt**  |-------------|
|`0x4d45000000000005`  |**Initial-daily receipt**                    |-------------|
|`0x4d45000000000003`  |**Cash-withdrawal receipt**                  |-------------|
|`0x4d45000000000003`  |**Cash deposit receipt**                     |-------------|
|`0x4d45000000000003`  |**Partial void card receipt**                |-------------|
|`0x4d45000000000003`  |**Partial void cash receipt**                |-------------|
|`0x4d45000000000003`  |**Complete voidd card receipt**              |-------------|
|`0x4d45000000000003`  |**Pos-receipt with discount reducing the base amount**|-------------|
|`0x4d45000000000003`  |**Pos-receipt with discount not reducing the base amount**|-------------|


## ftReceiptCaseFlag
This table expands on the values provided in table [ftReceiptCaseFlag in General Part](../../general/reference-tables/reference-tables.md#ftreceiptcaseflag) with values applicable to the Montenegrin market.

| **Value**            | **Description**                             | **Version** |
|----------------------|---------------------------------------------|-------------|
|----------------------|STO                                          |-------------|
|----------------------|Bad-Invoice                                  |-------------|
