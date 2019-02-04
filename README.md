# install loopback CLI
`npm install -g loopback-cli`

# generate the project
`slc loopback`

# install mongoDB conenctor
`npm install loopback-connector-mongodb --save`

# create our datasource
`lb datasource`

# create our model
`lb model`

# install angular 2 generator
`npm install --save-dev @mean-expert/loopback-sdk-builder`

# generate sdk angular 2 services
`./node_modules/.bin/lb-sdk server/server.js ../iot-uniovi-ui/src/app/shared/sdk`

# to start server
`npm start* `

# install pm2 cluster service
`npm install -g pm2`

# to start server cluster with pm2
`pm2 start`
`pm2 restart`
`pm2 stop`
`pm2 monit`