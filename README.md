# liquibase_extension_example
This is a Liquibase extension example.
It will convert any `NUMBER(1,0)` datatype in a modeled changeset to `BOOLEAN` when running against a PostgreSQL database during runtime update. </br>
or</br>
It will generate a formatted sql changelog and convert any `NUMBER(1,0)` datatype to a `BOOLEAN` when the resulting changelog name includes `postgresql` database name.
For example:</br>
`liquibase --changeLogFile=mychangelog.postgresql.sql generateChangeLog`


# Notes
Keep in mind that this is a community example and is not part of the Liquibase source code.
Any use of this code/artifacts will be under the responsibility of the user.
