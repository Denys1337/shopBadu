#DEV <br />
Do `npm install`
##### Run any `dev` script from `package.json`, for example `npm run dev:prod`

`dev:prod` - survey plugin will be used from production server <br />
`dev:stage` - survey plugin will be used from staging server

#Build

`build:prod` - survey plugin will be used from production server <br />
`build:stage` - survey plugin will be used from staging server <br />
<br />
All builded files will be minified. 


#Devops
`build:prod` - for production<br />
`build:stage` - for staging
<br />
After build copy content of the public folder to the destination folder.

#Configs
`env.config.json` - configuration file for environments. You can specify any values in that file and use it for build (`gulpfile.js`).

## test ci