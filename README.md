1.Setting app severs
serverless login
cd appSever
npm install .
npm update --save
npm audit fix
serverless
serverless deploy --verbose

2. Setting interface app
cd interfaceApp
npm update --save
npm audit fix --legacy-peer-deps
npm install --save-dev
npm run start
