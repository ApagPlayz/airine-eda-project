| Column Name             | Type   | Description                                                           |
|------------------------|--------|-----------------------------------------------------------------------|
| Month                  | string | Name of the month for the record (e.g., "January")                    |
| AustralianPort         | string | Name of the Australian airport/port (e.g., "Sydney")                  |
| ForeignPort            | string | Name of the foreign airport/port (e.g., "Los Angeles")                |
| Country                | string | Country where the foreign port is located (e.g., "United States")     |
| Passengers_In          | int    | Number of inbound passengers to Australia from this route/month        |
| Freight_In_(tonnes)    | float  | Inbound freight carried to Australia (in tonnes)                       |
| Mail_In_(tonnes)       | float  | Inbound mail carried to Australia (in tonnes)                          |
| Passengers_Out         | int    | Number of outbound passengers from Australia for this route/month      |
| Freight_Out_(tonnes)   | float  | Outbound freight from Australia (in tonnes)                            |
| Mail_Out_(tonnes)      | float  | Outbound mail from Australia (in tonnes)                               |
| Passengers_Total       | int    | Total passengers (inbound + outbound) for this city pair/month         |
| Freight_Total_(tonnes) | float  | Total freight (inbound + outbound) in tonnes                           |
| Mail_Total_(tonnes)    | float  | Total mail (inbound + outbound) in tonnes                              |
| Year                   | int    | Year of the record (e.g., 2019)                                        |
| Month_num              | int    | Month as a number (1 = January, 12 = December)                         |

**Notes:**
- All passenger counts are integer values (no decimals).
- All freight/mail values are in metric tonnes (may have decimals).

