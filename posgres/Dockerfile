# Base image
FROM postgres:latest

# Set environment variables
ENV POSTGRES_USER myuser
ENV POSTGRES_PASSWORD mypassword
ENV POSTGRES_DB mydatabase

# Copy initialization script
COPY init.sql /docker-entrypoint-initdb.d/

