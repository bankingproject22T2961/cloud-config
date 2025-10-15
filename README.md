# cloud-config
dossier de configurtion de tous les services
# docker
sudo docker run --hostname rabbitmq --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:management        
                             |                            |				|				|
                      nom de l'utilitaire                 |				|				|
                                                          |				|				|
                                          port interne au compteneur	|				|
                                          								|				|
                                           			port lue part la machine (externe)	|
                                          												|
                                          										nom du compteneur