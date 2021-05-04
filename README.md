# SQL QUERY COMPRESSOR

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/rahul1996pp/sqlquerycompress/blob/main/LICENSE)
- The script is used to compress insert statements.
- It takes text files only.
- we need to create text file with sql insert statements.
- make sure you must run the script in the same text files only.

**Example :-**
1.  `insert into MOCK_DATA (id, first_name, last_name, email, gender, ip_address) values (1, 'Teodor', 'Braz', 'tbraz0@cloudflare.com', 'Genderqueer', '64.30.47.28');`
2.  `insert into MOCK_DATA (id, first_name, last_name, email, gender, ip_address) values (2, 'Pooh', 'Spicer', 'pspicer1@sogou.com', 'Genderqueer', '98.12.203.122');`

**Output:-**

`insert into MOCK_DATA (id, first_name, last_name, email, gender, ip_address) values 
 (1, 'Teodor', 'Braz', 'tbraz0@cloudflare.com', 'Genderqueer', '64.30.47.28'),
 (2, 'Pooh', 'Spicer', 'pspicer1@sogou.com', 'Genderqueer', '98.12.203.122')`

## How to run script:
 `python sqlcom.py`

**Buy me a coffee : [click here](https://www.paypal.me/RahulPujari "Pay")**
