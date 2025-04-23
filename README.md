# chckpoint-atividade



primeiro erro-
houve a quebra do principio de responsabilidade unica,
onde a classe gerenciador de biblioteca esta fazendo diversa funçoes.

segundo erro-
princípio da inversão de dependência
ocorre no enviar email e enviar sms na classe gerenciadorbiblioteca

terceiro erro-
principio aberto-fechado no codigo acontece esse erro na função de realizaremrestimo pois inclui varias responsabilidade a da verificação de disponibilidade do livro  o envio de sms e emais a alteração do status do livros entre outras 


quarto erro - clean code -tratamento de erros 
no metodo  realizardevoluçao utilizou o return com o -1 para evitar o trabalho de tratar o erro gerado, oq eu pode causar mais problemas no futuro



quinta erro- clean code - codigo duplicado e mistura de responsabilidade
ocorre nos metodos realizaremprestico e realizardevolução,
acontece que esta realizando


