# Use the official Neo4j image as a base
FROM neo4j:latest

# Optional: If you have any custom configurations, you can copy them into the container
# Example: Copying a custom Neo4j configuration file
# COPY ./neo4j.conf /var/lib/neo4j/conf/neo4j.conf

# Optional: If you have plugins or other resources to include
# Example: Copying a custom plugin
# COPY ./plugins /var/lib/neo4j/plugins

# Environment variables for Neo4j
ENV NEO4J_AUTH=neo4j/test
# You can add more environment variables if needed

# Expose the necessary ports (7474 for HTTP and 7687 for Bolt)
EXPOSE 7474 7687

# Optional: You can set the default command to run when the container starts
# In this case, we simply start Neo4j
CMD ["neo4j"]
