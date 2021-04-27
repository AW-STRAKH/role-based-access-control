# Role based Acces Control 
## Hosted at:  ##https://rolebasedaccess-awatansh.herokuapp.com

Authentication used: Passport-jwt authentication adn role based control

## Routes:

Registration routes:

/register-user: To register user with username name email and password as req body 

/register-admin:  To register admin with username name email and password as req body

/register-superadmin:  To register superadmin with username name email and password as req body

Login Routes:


/login-user:Login a user with username and email as req body 

/login-admin:Login a admin with username and email as req body 

/login-super-admin:Login a superadmin with username and email as req body 


Roleupdationroute:


/updaterole: Only loggedin superadmin can change the role with username and role as req body


Resource rotes:

/user-protected : Resources viewable by loggedin user admin and superadmin

/admin-protected:  Resources viewable by  loggedin admin and superadmin

/super-admin-protected  Resources viewable by loggedin superadmin


Profileinfo :

/profile: Route to get the info of logged in user (handeled with JWT authentication)

## `Assumption`

ROLES:user,admin,superadmin

## `How to run:`

The app is hosted at Heroku 
Just hit the api endpoint with the required req to get the response.



## `Demo`:

[Registering user](https://user-images.githubusercontent.com/31369423/116231044-02ce8300-a776-11eb-8239-5b8b169ac6e2.PNG)


[Login user](https://user-images.githubusercontent.com/31369423/116231335-55a83a80-a776-11eb-8fcd-4994a266428c.PNG)












