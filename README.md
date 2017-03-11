Varnish docker container
===========

### Varnish environment variables
Varnish will use the following environment variables. You can override them if you want

| Environment Variable | Type | Default Value |
| -------------------- | -----| ------------- |
| VARNISH_BACKEND_HOST                  | String | 127.0.0.1 |
| VARNISH_BACKEND_PORT                  | String | 80        |
| VARNISH_SECRET                        | String | secret    |
| VARNISH_MEMORY_SIZE                   | String | 256M      |
| VARNISH_STORAGE_SIZE                  | String | 1024M     |
