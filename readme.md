![mqtt](./contents/mqtt.png)

## Deployment
`
helm install mqtt-broker . --set global.env.HOST=host.local -n mqtt
`


## Generating certificates

Server Certificates are inside certs folder.
Don't use the default values for production. You can generate new one everytime throught below command:

`
./certs/make-keys.sh
`
