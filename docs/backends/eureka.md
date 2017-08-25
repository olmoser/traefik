# Eureka backend

Træfik can be configured to use Eureka as a backend configuration:


```toml
################################################################
# Eureka configuration backend
################################################################

# Enable Eureka configuration backend
#
# Optional
#
[eureka]

# Eureka server endpoint.
# endpoint := "http://my.eureka.server/eureka"
#
# Required
#
endpoint = "http://my.eureka.server/eureka"

# Override default configuration time between refresh
#
# Optional
# default 30s
delay = "1m"

# Override default configuration template. For advanced users :)
#
# Optional
#
# filename = "eureka.tmpl"
```

Please refer to the [Key Value storage structure](/user-guide/kv-config/#key-value-storage-structure) section to get documentation on traefik KV structure.
