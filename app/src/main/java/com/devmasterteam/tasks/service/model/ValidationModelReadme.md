## Classe ValidationModel

A classe ValidationModel serve para passar se ou status do login retornou sucesso ou falha, ela também 
serve para retornar uma menssagem caso dê erro no login

Essa classe existe, porque sem ela, no LoginViewModel seria necessario criar duas variaveis pra serem observadas, 
o login (pra saber se deu falha ou não ao logar) e message (pra retornar uma menssagem no caso da falha) 

