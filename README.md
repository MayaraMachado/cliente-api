# cliente-api
API Rest usando Django 


### cliente: 
- foto
- nome
- sobrenome
- cpf
- rg
- telefone
- email.

### endereco
- logradouro,
- bairro
- cidade
- estado
- numero.

##Rotas: 

- api/cliente com funcionalidades GET, POST
- api/cliente/<ph-cliente> com funcionalidades GET, PUT, PATCH, DELETE
- api/cliente/<pk-cliente>/endereco/ com funcionalidades GET, POST
- api/cliente/<pk-cliente>/endereco/<pk-endereco> com funcionalidades GET, PUT, PATCH, DELETE (ações caso pertença ao id)

##observações:

- DELETE remove logicamente 
- Não utilizar routers
