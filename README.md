﻿# d1-project12cms

 Version: 0.9.2

 Author  : Kouji Nakashima / kuc-arc-f.com

 date    : 2023/09/26

 update  : 2023/09/26 

***
### Summary

cloudflare D1 + workers, cms API sample

***
* wrangler.toml
```
name = "d1-project12ms"
main = "src/index.ts"
compatibility_date = "2023-08-09"
node_compat = true

[vars]
API_KEY = "123"

[[ d1_databases ]]
binding = "DB" # i.e. available in your Worker on env.DB
database_name = "db_astro3_13"
database_id = "123"
```
***

