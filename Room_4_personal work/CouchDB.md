---
creation_date: 24.01.17
last_modified: 
note_type: basic
category: 
aliases: 
tags: 
Status:
  - Working
PARA:
---
``` docker web editer
version: "3.9"
services:
  couchdb:
    image: couchdb
    container_name: CouchDB
    hostname: couchdb
    mem_limit: 2g
    network_mode: host
    volumes:
      - /volume1/docker/couchdb:/opt/couchdb/data:rw
    environment:
     COUCHDB_USER: youde1230
     COUCHDB_PASSWORD: ehdgus97
    restart: on-failure:5
```

