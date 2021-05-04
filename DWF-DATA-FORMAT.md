# DWF Data Format

The JSON is generated in https://github.com/distributedweaknessfiling/dwf-request/blob/main/dwf-bot/DWF/DWFRepo.py which is the best documentaiton currently (it reflects reality)

## Data types

We use the standard JSON data types. 

### Dates and times

Dates and times should use RFC3339 (https://tools.ietf.org/html/rfc3339) and not ISO8601 for the ismple reason that RFC3339 is freely available to read and implement.
