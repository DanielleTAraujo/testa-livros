Situa��o:
- Criei tr�s tests no Selenium:
	- Teste 1: Executa a valida��o dos testes entre Submarino X Amazon
	- Teste 2: Executa a valida��o dos testes entre Submarino X Livraria Cultura
	- Teste 3: Executa a valida��o dos testes entre Submarino X Amazon e Submarino X Livraria Culura
Observa��o: Criei tr�s testes, pois facilita para a pessoa que vai rodar os testes, no caso de falha, verificar qual falhou e qual passou.

Situa��o: 
- Como o teste pede que a valia��o seja feita atrav�s do ISBN, se alguns dos sites (Submarino, Livraria Cultura ou Amanzon) n�o tiverem este campo, o teste vai falhar.
Observa��o: (1) como futura melhoria para o script, n�o achando o ISBN, o script deve procurar pelo nome do livro e (2) como futura melhoria para no script, o script dever� melhorar a mensagem de falha explicando que n�o encontrou o ISBN. Atualmente, o script falha, a mensagem de erro no log n�o � clara.

- A valida��o do autor falha caso os sites configurem o digitarem nome do autor de maneira diferente (exemplos: "Agatha Christie" e "Christie, Agatha" / "Antoine de Saint-Exup�ry" e "Antoine De Saint-Exupery) 
Observa��o: para facilitar a revis�o dos resultados dos testes, como futura melhoria do script, a mensagem de erro pode ser enviada para o usu�rio atrav�s de uma conta de email configurada. 