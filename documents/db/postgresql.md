CREATE USER athena WITH PASSWORD 'athena';
CREATE DATABASE athena OWNER athena;
GRANT ALL PRIVILEGES ON DATABASE athena TO athena;