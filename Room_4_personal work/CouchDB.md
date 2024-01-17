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
version: '3'
services:
  couchserver:
    image: couchdb
    restart: always
    ports:
      - "22345:5984"
    environment:
      - COUCHDB_USER=kill9749
      - COUCHDB_PASSWORD=Wnsud2006^
    volumes:
        - /volume1/docker/couchdb:/opt/couchdb/data
```

[How to Install CouchDB on Your Synology NAS – Marius Hosting](https://mariushosting.com/how-to-install-couchdb-on-your-synology-nas/)
[Install CouchDB using Docker and Docker-compose](https://medevel.com/tutorial-install-couchdb-with-docker/)