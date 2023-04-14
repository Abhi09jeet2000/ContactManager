# ContactManager

# Endpoints
 
#Base Url- http://localhost:5001

#1. [POST-METHOD] : '/register' ~ registering user

#2. [POST-METHOD] : '/login' ~ signing in user

#3. [GET-METHOD] : '/current' ~ current details of loggedin user {only works if jwt token is valid}

#4. [GET-METHOD] : '/' ~ get all contacts { only works if jwt token is valid }

#5. [POST-METHOD]: '/' ~ create contact {only works if jwt token is valid }

#6. [GET-METHOD]: '/:id' ~ get particular contact by id {only works if jwt token is valid }

#7. [PUT-METHOD]: '/:id' ~ for updating particular contact {only works if jwt token is valid }

#8. [DELETE-METHOD]: '/:id' ~for deleting particular contact {only works if jwt token is valid }

# MongoDB Cluster

User Collection

<img width="1504" alt="User Collection" src="https://user-images.githubusercontent.com/65527851/231958801-d567ffd0-143d-4e8c-93d9-593dd691c740.png">

Contact Collection

<img width="1512" alt="Contact Collection" src="https://user-images.githubusercontent.com/65527851/231958881-4e0a7663-dccc-4357-bcfb-78fdcc5dec55.png">

