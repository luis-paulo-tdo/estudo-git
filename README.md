# Curso Git e GitHub: Dominando Controle de Versão do Código

## 1. Analisando Mudanças

### 1.1. Apresentação
- O curso ensinará os conceitos de branches, git merge e git rebase.
- Aprofundará em muitas coisas a respeito do Git como um todo.
- Ensinará sobre a visualização de alterações pelo git log.
- Ensinará sobre a busca de commits específicos por parâmetros.
- Ensinará a respeito da visualização das diferenças de commits.
- Ensinará o que são as branches, como utilizá-las e como uní-las.
- Ensinará sobre a manipulação e a gravação de alterações.
- Ensinará sobre as tags para criar versões e releases do projeto.
- Ensinará comandos específicos do git para rastrear as mudanças.
- O curso fará bastante uso do git em versão de terminal.

### 1.2. Parâmetros do Log
- O comando `git log` possibilita ver o log de commits de uma branch.
- Ele mostra o hash do commit, o autor, a data e a mensagem.
- Podemos querer ver mais ou menos informações em certas situações.
- O `git log --online` traz o histórico de commit mais resumido.
	- Somente o hash e a mensagem do commit são exibidas.
- O `git log -p` traz informações mais completas do histórico.
	- Além das informações do `git log`, traz os diffs dos arquivos.
- O `git log --graph` mostra a linha do tempo dos commits.
	- Serve muito para a rastreabilidade de outras branches.
- O `git log --format` permite customizar o histórico dos commits.
	- O format recebe uma expressão própria do git para customização.
	- A expressão pode ser aprendida com o comando `git help`.

### 1.3. Vendo as Alterações
- Para que possamos ver a alteração de um determinado commit, exite o `git show`.
- Passamos para ele o hash do commit e ele exibirá todos os detalhes do commit.
- Diferente do git log, ele exibe os detalhes apenas do commit que foi passado.
- É possível ver detalhes sobre qualquer comando acrescentando o --help.
- Com isso, podemos saber mais sobre o git show ao fazer `git show --help`.
	- Sempre que o parâmetro vier entre colchetes, ele é opcional.
- O hash passado para o `git show` é opcional, e se não houver, ele exibe o HEAD.
	- O HEAD nada mais é do que o último commit feito na branch local atual.

### 1.4. Próximas Alterações
- O `git status` mostra qual é a branch atual e se tem alterações para adicionar.
- O `git diff` mostra a diferença do que foi feito com o que está em HEAD.
- O `git diff` também permite ver a diferença entre dois commits diferentes.
	- Basta apenas passar a hash do commit mais antigo e a hash de um posterior.
