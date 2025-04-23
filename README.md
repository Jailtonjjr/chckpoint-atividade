# chckpoint-atividade



primeiro erro-
houve a quebra do principio de responsabilidade unica,
onde a classe gerenciador de biblioteca esta fazendo diversa funçoes.

segundo erro-
princípio da inversão de dependência
ocorre no enviar email e enviar sms na classe gerenciadorbiblioteca

terceiro erro-
principio aberto-fechado no codigo acontece esse erro 


quarto erro-
principio de segregação de interface 
podemos notar que com a adição de interfaces, acontece um problema de multiplas interfaces que podemos resolver criando uma nova interface que será responsavel por aceitar as outras interface



quinta erro- clean code - codigo duplicado e mistura de responsabilidade
ocorre nos metodos realizaremprestico e realizardevolução,
acontece que esta realizando


sexto erro - clean code -tratamento de erros 
no metodo  realizardevoluçao utilizou o return com o -1 para evitar o trabalho de tratar o erro gerado, oq eu pode causar mais problemas no futuro
