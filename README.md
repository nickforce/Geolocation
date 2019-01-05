# SFDX  App

## Dev, Build and Test

### Validate App in a new Scratch Org

#### Create a new scratch org:
sfdx force:org:create -f config/project-scratch-def.json -a GeoTestOrg

#### Push your local source and metadata to the scratch org:
sfdx force:source:push -u GeoTestOrg

#### Assign your permission set:
sfdx force:user:permset:assign -n Geolocation -u GeoTestOrg

#### Load your sample data into the new scratch org:
sfdx force:data:tree:import -f data/Account.json -u GeoTestOrg

#### Open your org:
sfdx force:org:open -u GeoTestOrg

## Resources

## Description of Files and Directories


## Issues


=======
# Geolocation
SFDX sample app

