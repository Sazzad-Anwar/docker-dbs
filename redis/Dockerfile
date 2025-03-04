# Use the official Redis Alpine image for a smaller footprint
FROM redis:7.2-alpine

# Set Redis configuration (optional, can be overridden in redis.conf)
COPY redis.conf /usr/local/etc/redis/redis.conf

# Expose Redis default port
EXPOSE 6379

# Start Redis with custom config
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
