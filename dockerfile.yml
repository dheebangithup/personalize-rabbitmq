# Use RabbitMQ official image with management plugin enabled
FROM rabbitmq:3-management

# Expose both AMQP port (5672) and Management UI port (15672)
EXPOSE 5672
EXPOSE 15672

# (Optional) Set default user and password via build arguments or environment
# Better to pass these via Render Environment tab rather than hardcoding
ENV RABBITMQ_DEFAULT_USER=${RABBIT_MQ_USER}
ENV RABBITMQ_DEFAULT_PASS=${RABBIT_MQ_PASSWORD}

# No extra commands needed — RabbitMQ will auto-start with management enabled
