oc new-app --name myapp \
--build-env \ 
nodejs:10~https://github.com/leonbu/DO288-apps#app-config \
--context-dir app-config
