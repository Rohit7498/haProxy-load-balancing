# haProxy-load-balancing
Used HAproxy to setup load balancing with ACL (layer 7) and docker to run multiple servers

## Built some pretty good layer 7 proxy with Access control conditions as well
## Summary:

1:  get / : Round robins on all servers
2:  get / app1: Round robins on servers - 2222, 3333
3:  get / app2: Round robins on servers - 4444, 5555
4:  get / admin: denied acess - only can be accessed directly on the public ip

=> Also Played with load balancing a bit - least connection, source,



