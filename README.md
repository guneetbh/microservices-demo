# microservices-demo
Microservices demo 

Please note - jasypt uses key/salt to encrypth the  passwords/secrets. We would need the key/salt while we decrypt the actual passwords.
Again Key shoud not be stored in  repo or environment files.  Best way is to store these keys as environment variable where we intent to deploy our application. 

Linux: export JASYPT_ENCRYPTOR_PASSWORD='Demo_Pwd!2020' or ./bashrc  for permanent storage.
Windows: add environment variable under user properties. 
