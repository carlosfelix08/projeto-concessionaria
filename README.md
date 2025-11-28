# projeto-concessionaria

## ⚙️ Instalação e Configuração

Para rodar este projeto em sua máquina local, você precisará de um ambiente de servidor web que suporte PHP e MySQL. Recomenda-se o uso de pacotes como **XAMPP**, **WAMP** ou **MAMP**.

### Pré-requisitos

*   Servidor Web (Apache)
*   Interpretador PHP (versão 7.x ou superior)
*   Banco de Dados MySQL/MariaDB

### Passos para Configuração

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
    cd NOME_DO_REPOSITORIO
    ```
    *(Substitua `SEU_USUARIO/NOME_DO_REPOSITORIO` pelo caminho real do seu projeto no GitHub.)*

2.  **Mova para o Diretório do Servidor:**
    Mova a pasta clonada (`NOME_DO_REPOSITORIO`) para o diretório de documentos do seu servidor web (ex: `htdocs` no XAMPP, `www` no WAMP).

3.  **Configuração do Banco de Dados:**
    a. Inicie o Apache e o MySQL no seu painel de controle (XAMPP/WAMP/MAMP).
    b. Acesse o **phpMyAdmin** (geralmente em `http://localhost/phpmyadmin`).
    c. Crie um novo banco de dados com o nome `hospedagem_db` (ou o nome que você utilizou no seu código PHP).
    d. **Importe o Schema:** Importe o arquivo SQL que contém a estrutura das tabelas (e dados iniciais, se houver).
        *   *Se você tiver um arquivo SQL, inclua-o na raiz do projeto e mencione o nome aqui (ex: `hospedagem_schema.sql`).*

4.  **Ajuste de Conexão (Se Necessário):**
    Verifique e ajuste as credenciais de conexão com o banco de dados no seu arquivo de configuração PHP (ex: `conexao.php` ou similar), garantindo que o `host`, `usuário`, `senha` e `nome do banco` estejam corretos para o seu ambiente local.

5.  **Acesso à Aplicação:**
    Abra seu navegador e acesse a aplicação pelo endereço:
    ```
    http://localhost/NOME_DO_REPOSITORIO/
    ```
    *(Substitua `NOME_DO_REPOSITORIO` pelo nome da pasta que você moveu para o `htdocs`.)*
