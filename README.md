# SFDX  App

## Dev, Build and Test

```
sfdx force:org:create -f config/project-scratch-def.json -a GeoTestOrg
sfdx force:source:push -u GeoTestOrg
sfdx force:user:permset:assign -n Geolocation -u GeoTestOrg
sfdx force:data:tree:import -f data/Account.json -u GeoTestOrg
sfdx force:org:open -u GeoTestOrg
```


## Resources


## Description of Files and Directories


## Issues


