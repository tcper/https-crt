# https-crt

brew install mkcert
mkcert -install
# cd to code directory
mkcert localhost
webpack-dev-server --cert ./localhost.pem --key ./localhost-key.pem
