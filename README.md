

## Para executar comandos
docker exec -it <NOME-DA-BASE> bash -c "source /home/oracle/.bashrc; sqlplus /nolog"

## To create users in bash session
connect sys as sysdba;
create user @user identified by @password;
GRANT ALL PRIVILEGES TO @user;

## To run datamodeler
datamodeler

## TO run 


## Docs
### Container
https://hub.docker.com/u/leonardovff/content/sub-0ff2ae4a-08d5-4df6-84f0-f4291b0d5b63

### Installation of data modeler and developer
https://stackoverflow.com/questions/41928566/installing-oracle-datamodeler-on-ubuntu-16-04
