vague idea being mentioned 

Master client data (mcd) infrastructure: 

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

2/9/2026

### MCD should answer 5 questions instantly:

- Who is the client? (identity)
- Where are they? (location & jurisdiction)
- What do they do? (operation & size)
- What do they buy? (services & value)
- How do they behave? (engagement & response)

including services in mcd 
```sql
has_irp -- true or false
has_ifta
has_drug_testing
has_clearinghouse
has_permits
has_eld
```

definig the marketing scope of mcd 
```sql
primary_email
email_valid_flag - true or false, valid or invalid 
phone_valid_flag
preferred_contact_method
marketing_opt_in
lead_source
```





