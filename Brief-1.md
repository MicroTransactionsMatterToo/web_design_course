# Brief for Website Development

## Client: Rhys Davies
## Problem
Rhys' is a 15, and is currently teaching himself digital music production. We both agreed that a site where he could collate and advertise his music/albums
## Solution: Create a website with a functional CMS, Music/Album gallery, and basic blogging capabilities

## Stakeholders
- Rhys Davies (Client)
- Me
- Rhys' parents (to an extent)

## Research
- Content Management Systems
- Music streaming
- Efficient resource storage online (blobs)

## Notes
While there is a standard for a relation database, the DB implemented for this will be only present, really to get the credits, as MongoDB is far better suited for storing blog-posts, and binary data than a relation database, which is ideal for values traditionally representable in a table. This system is not ideal for stuff with nested values (I'm aware of embedded tables).

The NoSQL database will be used to store blobbed picture files, post pages, and binary data. Users will be stored in a MySQL db, solely for the purpose of the database standard
