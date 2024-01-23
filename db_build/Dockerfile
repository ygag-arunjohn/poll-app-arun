FROM postgres:latest

# Set the environment variables
ENV POSTGRES_DB=polls
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=mypassword

# Copy the SQL file into the container
COPY init.sql /docker-entrypoint-initdb.d/
