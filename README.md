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
- O comando 'git log' possibilita ver o log de commits de uma branch.
- Ele mostra o hash do commit, o autor, a data e a mensagem.
- Podemos querer ver mais ou menos informações em certas situações.
- O 'git log --online' traz o histórico de commit mais resumido.
	- Somente o hash e a mensagem do commit são exibidas.
- O 'git log -p' traz informações mais completas do histórico.
	- Além das informações do 'git log', traz os diffs dos arquivos.
- O 'git log --graph' mostra a linha do tempo dos commits.
	- Serve muito para a rastreabilidade de outras branches.
- O 'git log --format' permite customizar o histórico dos commits.
	- O format recebe uma expressão própria do git para customização.
	- A expressão pode ser aprendida com o comando 'git help'.
