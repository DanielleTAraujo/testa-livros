Situação:
- Criei três tests no Selenium:
	- Teste 1: Executa a validação dos testes entre Submarino X Amazon
	- Teste 2: Executa a validação dos testes entre Submarino X Livraria Cultura
	- Teste 3: Executa a validação dos testes entre Submarino X Amazon e Submarino X Livraria Culura
Observação: Criei três testes, pois facilita para a pessoa que vai rodar os testes, no caso de falha, verificar qual falhou e qual passou.

Situação: 
- Como o teste pede que a valiação seja feita através do ISBN, se alguns dos sites (Submarino, Livraria Cultura ou Amanzon) não tiverem este campo, o teste vai falhar.
Observação: (1) como futura melhoria para o script, não achando o ISBN, o script deve procurar pelo nome do livro e (2) como futura melhoria para no script, o script deverá melhorar a mensagem de falha explicando que não encontrou o ISBN. Atualmente, o script falha, a mensagem de erro no log não é clara.

- A validação do autor falha caso os sites configurem o digitarem nome do autor de maneira diferente (exemplos: "Agatha Christie" e "Christie, Agatha" / "Antoine de Saint-Exupéry" e "Antoine De Saint-Exupery) 
Observação: para facilitar a revisão dos resultados dos testes, como futura melhoria do script, a mensagem de erro pode ser enviada para o usuário através de uma conta de email configurada. 