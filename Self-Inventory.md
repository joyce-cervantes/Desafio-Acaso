# 📊 Testes - Self Inventory

## 🖥️ Cenários de Teste

| **ID** | **Cenário** | **Prioridade** | **Status** |
| --- | --- | --- | --- |
| CT001 | Validar início de sessão de usuário institucional com e-mail válido | Alta | Finalizado |
| CT002 | Validar funcionalidade de edição de cadastro | Alta | Finalizado |
| CT003 | Validar login de usuário institucional com e-mail inválido | Média | Finalizado |
| CT004 | Criação de cadastro sem preenchimento de campo obrigatório | Alta | Finalizado |
| CT005 | Testar funcionalidade de logout | Média | Finalizado |

## 📝 Casos de Teste

| **ID** | **Caso de Teste** | **Passos** | **Resultado Esperado** | **Resultado Obtido** |
| --- | --- | --- | --- | --- |
| CT001 | Início de sessão com sucesso | 1. Acessar a página inicial Self Inventory 2. Preencher e-mail institucional correto 3. Clicar em "Começar" | Sessão iniciada com sucesso | Passou ✅ |
| CT002 | Edição de dados de cadastro | 1. Estar com a sessão iniciada na página Self Inventory 2. Clicar no ícone de usuário no canto superior direito 3. Clicar em “editar perfil” | Informações editadas com sucesso | Passou ✅ |
| CT003 | Início de sessão com e-mail inválido | 1. Acessar a página inicial Self Inventory 2. Inserir e-mail incorreto 3. Tentar iniciar sessão | Exibir mensagem de erro “Este e-mail parece não estar registrado, por favor, verifique se você digitou corretamente” | Passou ✅ |
