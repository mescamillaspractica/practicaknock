
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


# to create user, make a POST with this stuff

{
	"user":
		{"name": "pepito",
		"email": "pepito@gmail.com",
		"password": "12345678",
		"password_confirmation": "12345678"
		}
}

#to authenticate, make a POST with this stuff

{
	"auth":{
		"email": "juanito@gmail.com",
		"password": "12345678"
	}
}