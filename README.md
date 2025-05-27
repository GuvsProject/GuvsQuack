# GuvsQuack
Projeto para desenvolvimento em angular com biblioteca em POUI

#Sistema de Empréstimo de livros particulares
	##Front (Angular) Prioridade(Guvs):
Homepage
Login
Perfil
Vitrine (marketplace)
Carrinho
Pagamento
Acompanhar pedidos

	##Back(FastAPI) Prioridade(EQ):
Cadastro/Edição de livro
Empréstimo/Devolução do livro
Criação de alerta para livros vencidos
Conexão com o DB
Criação/Edição de usuário

	##DB(Supabase/Firebase) Prioridade(Quack):
Usuários
Livros
Pedidos (id)
Empréstimos un. livro (FKey = pedidos.id)
