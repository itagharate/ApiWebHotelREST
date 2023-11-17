Projet pour serie de TP SERVICE WEB REST 
Contient 2 solutions : 
ClientAgence qui represente une agence qui consomme les services du serveur, et permet une interaction avec une interface
ServiceHotelREST qui est une api web REST, le controlleur Hotel permet :
1. Retourner une liste de Chambre de plusieurs hotels (Methode GET) https://localhost:44367/api/Hotel/GetHotel/nbLits
nbLits = 1 permet de retourner les chambre avec 1 lit par exemple.(chaque chambre avec une image)
2. Permet de procéder à la reservation d'une chambre.(Methode POST) https://localhost:44367/api/Hotel/PostReserv
le client peut passer un JArray avec les chams remplis que le serveur traite pour retourner un Numero de reservation.
