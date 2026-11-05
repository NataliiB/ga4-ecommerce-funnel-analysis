| Field | Type | Meaning |
| --- | --- | --- |
| event_name | STRING | Name of the user action |
| event_date | STRING | Date of the event in YYYYMMDD format |
| user_id | STRING | Unique number for each user |
| device | STRING | Name of the user's device, on which the action was done |
| geo | RECORD | Information about user's location |
| event_timestamp | INTEGER | The time of action in ms |
| app_info | RECORD | Information about application, in what action was done? for example: version, install_source etc. |
| purchase_revenue | FLOAT | Amount, that user has paid |
| unique_items | INTEGER | Quantity of unique items in order |

## Limitations
The data is obfuscated: some values ​​have been replaced with <Other>, NULL, or empty strings.