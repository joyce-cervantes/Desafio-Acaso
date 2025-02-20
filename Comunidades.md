# 📊 Testes - Comunidades

## 🖥️ Cenários de Teste

| **ID** | **Cenário** | **Prioridade** | **Status** |
| --- | --- | --- | --- |
| CT001 | Validar cadastro de usuário com dados válidos | Alta | Finalizado |
| CT002 | Validar início de sessão com e-mail inválido | Alta | Finalizado |
| CT003 | Testar funcionalidade de logout | Média | Finalizado |
| CT004 | Edição do cadastro com campos obrigatórios preenchidos | Média | Finalizado |
| CT005 | Edição do cadastro com campos obrigatórios não preenchidos | Média | Finalizado |

## 📝 Casos de Teste

| **ID** | **Caso de Teste** | **Passos** | **Resultado Esperado** | **Resultado Obtido** |
| --- | --- | --- | --- | --- |
| CT001 | Cadastro de usuário válido | 1. Acessar a página Comunidades
2. Clicar em "Criar Conta"
3. Inserir dados válidos conforme solicitado
4. Confirmar criação | Usuário cadastrado com sucesso | Passou ✅ |
| CT002 | Início de sessão com e-mail inválido | 1. Acessar a página inicial de Comunidades
2. Inserir e-mail incorreto
3. Tentar iniciar sessão | Exibir mensagem de erro “Esta e-mail parece não estar registrado, por favor, verifique se você digitou corretamente ou crie uma nova” | Passou ✅ |
| CT003 | Realizar encerramento de sessão | 1. Estar com a sessão iniciada
2. Clicar no ícone/foto de usuário no canto superior direito
3. Clicar em “sair de acaso” | Usuário encerra a sessão em acaso com sucesso | Passou ✅ |

## 🐞 Relatório de Bugs e Defeitos

| **ID** | **Bug** | **Prioridade** | **Evidências** | **Status** |
| --- | --- | --- | --- | --- |
| B001 | Mensagem de erro quando o usuário tenta iniciar sessão com e-mail inválido está cortada no final | Baixa | [Imagem](https://loom.com/i/875aa6400f444275a3333273a820de20) | Pendente |
| B002 | Permite que a pessoa usuária edite seu cadastro removendo informações dos campos obrigatórios e deixando-os sem preenchimento | Alta | [Vídeo](https://www.loom.com/share/2a87dd29c22244478845b1417d79b53a?sid=3ef55348-91e7-4a33-86cc-18bbfbf1acf8) | Pendente |

## ✨ Melhorias Sugeridas

| **ID** | **Descrição** | **Melhoria Sugerida** | **Evidências** | **Status** |
| --- | --- | --- | --- | --- |
| M001 | Na tela de onboarding, no momento de selecionar sobre quais assuntos você quer aprender, não é possível colocar algum tema fora das opções listadas | Poder inserir quais assuntos a pessoa usuária deseja aprender/ensinar mesmo que não esteja listado, pois isso pode estar limitando os assuntos a serem abordados na plataforma | [Vídeo](https://www.loom.com/share/08d59393052648ebb621a2635a071364?sid=9566cd4e-99f9-49d4-a761-3fb670327997) | Pendente |
