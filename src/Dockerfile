FROM python:3.8-slim

# Install PostgreSQL command-line tools
RUN apt-get update && apt-get install -y postgresql-client-15

# Copy the source files 
COPY elt.py .

# Set the default command to run the ELT script
CMD ["python", "elt.py"]