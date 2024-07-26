# 3.6 Schema

**Schema** defines the format of data associated with IDs. The main concern for schema is how to manage the data passed between IDs in ALMA. The functions required of schema are as follows:

* Stored data cannot be read by the admin when it enters via SSH.
* When sharing is requested, schema should be able to realize disclosure of "existence of data" itself, range specification such as "partial disclosure of data" or "disclosure of all data," and time limit specification such as "can be retrieved only once," "can be retrieved only today," or "can be retrieved permanently.

From this perspective, we believe the following technologies are important elements.

* Selective disclosure
* Zero-knowledge proof
* Role-based access control

