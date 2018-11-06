# cradle sql

> Manage Cradle SQL databases.

- Rebuild the database schema:

`cradle sql build`

- Rebuild the database schema for a specific package:

`cradle sql build {{package}}`

- Truncate the entire database:

`cradle sql flush`

- Truncate the database tables for a specific package:

`cradle sql flush {{package}}`

- Populate the tables for all packages:

`cradle sql populate`

- Populate the tables for a specific package:

`cradle sql populate {{package}}`