# README
RESTFUL routes 

Prefix       VERB   URI PATTERN        Controller#Action
pets         GET    /pets              pets#index
new_pet      GET    /pets/new          pets#new     #displays a form
             POST   /pets/             pets#create  #submit the information
edit_pet     GET    /pets/:id/edit     pets#edit    #display edit form
             PATCH  /pets/:id          pets#update  #submit the edited form information
pet          GET    /pets/:id          pets#show    #dispay a particular pet
             DELETE /pets/:id          pets#destroy #deletes a particular pet