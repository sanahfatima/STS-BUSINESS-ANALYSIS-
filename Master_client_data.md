vague idea being mentioned 

Master client data infrastructure: 

Client > client id > client log in username is their id (tdk) 

Client identification 
Client documents 

Client table: 
```sql
CREATE TABLE clients (
    dot_number            BIGINT,
    legal_name            TEXT,
    dba_name              TEXT,
    physical_state        VARCHAR(2),
    physical_city         TEXT,
    carrier_operation     TEXT,
    hm_flag               CHAR(1),
    passenger_flag        CHAR(1),
    operating_status      TEXT,
    power_units           INT,
    drivers               INT,
    created_dt            DATE
);
```
Similar to fmcsa, need more columns 
