# Setting up NPM with Artifactory

Locate the `.nmprc` file and update the contents with the following:

```sh
registry=https://<your_org>.jfrog.io/artifactory/api/npm/npm/
email=<user>.<email>@<organization>.com
always-auth=true
//<your_org>.jfrog.io/<your_org>/api/npm/npm/:_authToken="zmxncbvAlSkjDHfgaKASDkllOWirYTuRytOeITgdHEUeoW3E"
//<your_org>.jfrog.io/artifactory/api/npm/npm/:_authToken="zmxncbvAlSkjDHfgaKASDkllOWirYTuRytOeITgdHEUeoW3E"
always-auth=true
```
