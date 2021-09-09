# People API - cadastro de pessoas

# Sobre o projeto

 API com arquitetura REST desenvolvida com Spring Boot, possui funcionalidades que reforcam o conceito REST em um CRUD completo para 
 gerenciamento de pessoas de uma organização, ao fim o Deploy foi feito na nuvem (Heroku) com a integração github deploy.


A aplicação tem como objetivo "gerenciar o cadastro de pessoas", suas funcionalidades são: criação, listagem, atualização e exclusão de pessoas. 



## Endpoint get master - postman 
![Web 1](https://github.com/jbdrumond/assets/blob/fef477e395e6fd8b96352fa9aee0049ef9a06e7b/postman.jpg) 



# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- Lombok
- h2 
- JPA / Hibernate
- Maven

## Implantação 

- URL para chamada Heroku:   https://peopleapi-jb.herokuapp.com/api/v1/people
- Banco de dados in-memory: h2 

_Ex: **body application/json POST**_

```javascript
{
	"firstName": "nome",
	"lastName": "sobrenome",
	"cpf": "000.000.000-00",
	"phones":[
	    {
	    	"type": "MOBILE",
	    	"number": "(16)999159900"
	    }	
		
	]
} 
```



# Autor

José Brasil Drumond Filho
