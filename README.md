# Ansible Role for configure guacamole.

**summary**
This role is for configuring guacamole. 
Look in the tasks directory for each configuration.
All configurations are held atomically via their own files. 

## Variables that have to be defined
First look at tasks/0_check.yml

| variable | description |
| -------- | ----------- |
| postgres.data_dir | Path to store Postgres-Data |
| postgres.db_name | DB name |
| guacamole.data_dir | Path to store Guacamole-Data |
| guacamole.home | Path to the Guacamole User |
| version_tags.guacd | Version Tag of guacd |
| version_tags.guacamole | Version Tag of guacamole |
| version_tags.postgres | Version Tag of postgres |
| postgres.auto_create_accounts | auto create user accounts (bool) |