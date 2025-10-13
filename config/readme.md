# Configurações do Projeto

Nesta pasta ficam os **arquivos e parâmetros de configuração** usados pelo sistema.  
Eles definem variáveis de ambiente, conexões com o banco de dados Oracle e ajustes necessários para execução do projeto.

---

##  Arquivos

### `oracle.env.exemplo`
Modelo de arquivo de variáveis de ambiente para configuração do Oracle.  
Serve como **exemplo de estrutura** — não contém credenciais reais.

Exemplo de conteúdo:
```env
# ==============================
# Exemplo de configuração Oracle
# ==============================

# Endereço do banco Oracle (FIAP ou local)
ORA_DSN=oracle.fiap.com.br:1521/ORCL

# Usuário do banco Oracle (exemplo)
ORA_USER=seu_usuario

# Senha do banco Oracle (exemplo)
ORA_PASS=sua_senha