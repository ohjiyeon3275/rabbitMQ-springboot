### install erlang

brew install erlang

### install rabbitmq

brew install rabbitmq
export PATH=$PATH:/usr/local/sbin

Management Plugin enabled by default at http://localhost:15672

To restart rabbitmq after an upgrade:
  brew services restart rabbitmq
Or, if you don't want/need a background service you can just run:
  CONF_ENV_FILE="/opt/homebrew/etc/rabbitmq/rabbitmq-env.conf" /opt/homebrew/opt/rabbitmq/sbin/rabbitmq-server
==> Summary
🍺  /opt/homebrew/Cellar/rabbitmq/3.9.13: 1,390 files, 30.1MB
==> Running `brew cleanup rabbitmq`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).

