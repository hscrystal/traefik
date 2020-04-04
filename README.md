# traefik

### BasicAuth for Dashboard 
Note: all dollar signs in the hash need to be doubled for escaping. To create a user:password pair,
the following command can be used: **echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g**