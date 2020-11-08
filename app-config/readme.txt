oc new-app --name myapp \
--build-env npm_config_registry=\
https://registry.npmjs.org/repository/nodejs \
nodejs:10~https://github.com/leonbu/DO288-apps#app-config \
--context-dir app-config
