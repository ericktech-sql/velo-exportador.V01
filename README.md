# 🗄️ Velo Exportador

![GitHub release (latest by date)](https://img.shields.io/github/v/release/ericktech-sql/rundb-exportadorDeDados)


[![GitHub all releases](https://img.shields.io/github/downloads/ericktech-sql/rundb-exportadorDeDados/total)](https://github.com//ericktech-sql/rundb-exportadorDeDados/releases)

[![License](https://img.shields.io/badge/licença-MIT-blue)](./LICENSE)

**Exporte seus dados corporativos para Excel com agilidade.**  
Conecte-se a múltiplos bancos de dados e extraia cadastros de **Produtos**, **Clientes/Fornecedores**, **Contas a Pagar** e **Contas a Receber** em planilhas organizadas, sem precisar escrever uma linha de SQL.

---

## 📌 Sobre o Projeto

O **Velo Exportador** foi criado para simplificar a rotina de quem precisa exportar dados, gerando planilhas prontas para serem importadas no Velo Sistema.

**Status do Projeto:** 🟢 Em desenvolvimento ativo.  
*Este repositório serve como vitrine e central de downloads. O código-fonte permanece em um repositório privado durante a fase de construção.*

---

## ✨ Funcionalidades Principais

- ✅ **Módulos de Negócio Específicos:**
    - 📦 **Produtos:** Código, descrição, preço de venda, estoque atual, NCM, unidade de medida e etc.
    - 👥 **Pessoas:** Clientes e Fornecedores.
    - 💰 **Financeiro:** Contas a Pagar e Contas a Receber.
- ✅ **Compatibilidade com os Principais SGBDs:** Funciona com MySQL, PostgreSQL, SQL Server, Firebird e SQLite.
- ✅ **Formatação Automática:** As planilhas geradas já saem com colunas formatadas corretamente.

---

 🗄️ Bancos de Dados Suportados

| SGBD | Status |
| :--- | :---: |
| **Firebird** | ✅ Concluído |
| **MySQL** / MariaDB | ✅ Concluído |
| **PostgreSQL** | ✅ Concluído |
| **Microsoft SQL Server** | ✅ Concluído |
<!-- ##
| **SQLite** | 🔄 Em planejamento |
| **Oracle Database** | 🔄 Em planejamento |
-->

## 🗄️ Sistemas mapeados

| **Host** | **Firebird** | 
<br>
| **Gdoor** | **Firebird** |
<br>
| **Lc Sistema** | **Mysql** |
<br>
| **Sistema Hiper (novo)** | **SQL Server** |
<br>
| **Sistema Hiper (Legado)** | **SQL Server** |
<br>
| **Sistema Uniplus** | **PostgreSQL** |


<!--
| **MySQL** / MariaDB | 🔄 Em planejamento |
| **PostgreSQL** | 🔄 Em planejamento |
| **Microsoft SQL Server** | 🔄 Em planejamento |
| **SQLite** | 🔄 Em planejamento |
| **Oracle Database** | 🔄 Em planejamento |
-->
---

## 📥 Download e Execução

O executável do **RunDB** é empacotado como um arquivo único e auto-contido para Windows.

➡️ **Acesse a [Página de Releases](https://github.com//ericktech-sql/rundb-exportadorDeDados/releases) para baixar a versão mais recente.**
<br><br>
ou clique para baixar: <br><br>
https://github.com/ericktech-sql/rundb-exportadorDeDados/releases/download/exportador-de-dados/RunDB.-.Exportador.de.dados.zip

### Como Instalar:
1. Faça o download do arquivo.
2. Instale o aplicativo.
3. Execute o arquivo no atalho na área de trabalho `Velo Exportador`.

> ⚠️ **Nota de Segurança:** Por ser um software independente, o Windows SmartScreen pode exibir um aviso. Isso ocorre porque o aplicativo não possui um certificado digital de assinatura de código. Clique em **"Mais informações"** e depois em **"Executar mesmo assim"**.

---

## 🖼️ Interface do Sistema (Screenshots)

*Espaço reservado para você inserir imagens da tela do programa.*

### Tela de Boas-Vindas
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/dd507707-4d5d-4ae9-951e-69d9e06eea43" />
*Selecione o driver do seu banco de dados e preencha as credenciais de acesso.*
<!--
### 2. Módulo de Cadastro de Produtos
<img width="1918" height="1021" alt="image" src="https://github.com/user-attachments/assets/1c9f0c9c-bbd6-4757-8a2a-ae4120ff46e7" />
*Visualize a lista de produtos, e exporte os dados selecionados.*

### 3. Módulo de Cadastro de Pessoas (clientes e fornecedores)
<br>

### 4. Módulo Financeiro (Contas a Pagar/Receber)
<br>
-->
---

## 🚀 Como Usar (Passo a Passo)

1.  Abra o **Velo Exportador**.
2.  Abra o card do sistema desejado, clique em Configurar banco de dados, configure a **"Conexão"** e salve.
3.  Após conectar, navegue pelos cards:
    - `Exportar Produtos`
    - `Exportar Pessoas`
    - `Exportar Contas a Receber`
    - `Exportar Contas a Pagar`
4.  Clique em **"Visualizar"** para visualizar a prévia na grade.
5.  Pressione **"Exportar para Excel"**.
6.  Selecione o destino do arquivo e salve.

---

## 🤝 Suporte e Feedback

Encontrou algum comportamento inesperado no **RunDB**? Tem alguma sugestão de melhoria ou de um novo banco de dados que gostaria de ver suportado?

Utilize a aba de **[Issues](https://--)** aqui no GitHub para reportar. Sua participação é fundamental para a evolução da ferramenta!

---

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais informações.

---

**Desenvolvido por Erick Tech**  
*Transformando consultas SQL em dados exportados.*
