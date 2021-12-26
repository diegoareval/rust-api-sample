# Rust api
'''
setup migrations and db: diesel setup --database-url connection_url

create migration: diesel migration generate migration_name

run migration: diesel migration run -- database-url connection_url
rollback migration: diesel migration redo -- database-url connection_url
generate schema: diesel print-schema > src\schema.rs
$connect: postgres://postgres:postgres@localhost/api_dev
'''