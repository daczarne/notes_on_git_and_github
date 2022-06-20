# From can be a base image, or in this case, a linux distribution
FROM alpine:3.11

# Copy the entrypoint script to the container
# Syntax: file to copy - destination path
COPY entrypoint.sh /entrypoint.sh

# Run the entrypoint script (use the path defined above)
ENTRYPOINT ["/entrypoint.sh"]
