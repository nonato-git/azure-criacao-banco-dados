# azure-criacao-banco-dados
Projeto para criação de instância de Banco de Dados no Azure - DIO
# Criação de Instância de Banco de Dados no Microsoft Azure

Este repositório foi criado como parte do desafio da DIO para praticar a criação e configuração de uma instância de Banco de Dados gerenciado na plataforma Microsoft Azure.

## 📌 Objetivo

- Praticar a criação de instâncias de banco de dados no Azure.
- Registrar os passos, dicas e boas práticas.
- Utilizar o GitHub para documentar e compartilhar o aprendizado.

## 🚀 Passos Realizados

1. Acesso ao portal [Microsoft Azure](https://portal.azure.com).
2. Criação de um novo recurso: **Banco de Dados SQL** (Instância Gerenciada).
3. Preenchimento dos dados principais:
   - **Nome do Banco de Dados:** exemplo-db
   - **Servidor:** exemplo-servidor.database.windows.net
   - **Autenticação:** Usuário e senha definidos.
4. Configuração de desempenho:
   - Escolha de plano de serviço (ex.: Básico, Standard, Premium).
5. Configuração de rede:
   - Definição de regras de firewall para permitir acesso ao banco.
6. Criação e provisionamento do Banco de Dados.
7. Teste de conexão utilizando Azure Data Studio ou outro cliente SQL.

## 💡 Dicas e Anotações

- **Login e Senha:** Anote com cuidado, são necessários para o acesso futuro.
- **Segurança:** Sempre configure IPs permitidos no firewall do servidor.
- **Backups:** O Azure cria backups automáticos, mas é bom validar a configuração.
- **Custo:** Atenção ao plano escolhido para evitar cobranças inesperadas.

## 🖼️ Capturas de Tela

Exemplo da criação de uma instância de banco de dados no portal do Azure:

![Criação da Instância de Banco de Dados](./images/Imagem-banco-azure.png)

## 📚 Referências

- [Documentação Oficial Azure - Criar Instância de Banco de Dados](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-get-started-portal)
- [GitHub Markdown Guide](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
