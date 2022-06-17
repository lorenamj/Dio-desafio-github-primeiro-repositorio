# Chave SSH

E uma etapa que permite a conexão entre duas maquinas publica e privada.

## *Como faço isso de forma segura ?

 Para que isso seja feito é necessário alocar a chave SSH ou token em ambos os sistemas, tornando assim uma conexão segura criptada entre duas maquinas *(servidor e remoto)*.  



## GIT 	

Acessar o GIT Bash 

:arrow_down:

 digitar os comando *ssh-keygen -t ed25519 -C email que usa no github*

:arrow_down:(enter)

enter file in which to save the key(local onde foi salva):

:arrow_down: (enter)

*Digitar uma senha*

:arrow_down: (enter)

*Digitar senha novamente*

:arrow_down:(enter)

:ok:(chave foi salva)

Ctrl+L 

:arrow_down:

digitar os comandos *cd /c/users/nome adm computador/.ssh*

:arrow_down:(enter)

ls

:arrow_down:

id-ed25519  id_ed25519.pub

(relacionadas chave publica e privada)

:arrow_down:

digitar comando *cat* para vizualizar id_ed25519.pub

copia e cola no Github.



# GITHUB



Acesse o Perfil   https://github.com/                             

​       :arrow_down_small:                                                                                       

Settings                                                                            

​      :arrow_down_small:

SSH Keys

​     :arrow_down_small:

New SSH Key.

(nome da chave e copiar e colar )





 *Caso não queira reinserir sua senha toda vez que  que usar a chave SSH, você pode adicionar sua chave ao agente SSH , que gerencia suas chaves SSH e lembra sua senha secreta.*