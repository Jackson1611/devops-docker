# Start from Ubuntu 22.04
FROM ubuntu:22.04

# Install curl
RUN apt-get update && apt-get install -y curl

# Copy the script file
COPY script.sh /usr/local/bin/

# Set script file as executable
RUN chmod +x /usr/local/bin/script.sh

# Set the script to run on container start using CMD
CMD ["/usr/local/bin/script.sh"]
