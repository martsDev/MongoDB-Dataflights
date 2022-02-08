# Boas vindas ao repositório do projeto DataFlights!!

# Sobre o projeto 🛠

Neste projeto o objetivo era praticar os principais comandos de busca, inserção, filtragem e exclusão de dados em um banco de dados MongoDB

# Habilidades 📚

- Buscar documentos no banco
- Usar filtros na busca
- Deletar documentos conforme filtro
- Contar documentos compreendidos nos filtros pedidos
- Inserir documentos no banco


---

# Quer testar o projeto? 👨‍💻

- Baixe o projeto: git clone

- Entre no diretório do projeto e instale as dependências: cd mongodb-dataflights && npm install

- Siga as instruções para restaurar o banco de dados e rode as queries no seu terminal

---

## Instruções para restaurar o banco de dados `dataFlights`

1. Abra o terminal e conecte-se à sua instância local do **MongoDB**. Se você receber uma mensagem de erro com uma mensagem como ***Connection refused***, tente reiniciar sua instância clicando ([nesse link do course](https://app.betrybe.com/course/content/d396e5a2-d5c9-4f3a-b723-1a1d3ea06b3d)) e através do menu lateral, no item `Conectando`.

2. Agora que você tem certeza de que a sua instância está no ar e que você está conectado a ela, digite `exit`. Você voltará ao terminal para iniciar a importação dos dados.

3. Na raiz do diretório do projeto, execute o seguinte comando que fará a restauração da base de dados `dataFlights`:
    ```sh
    DBNAME=dataFlights ./scripts/resetdb.sh assets
    ```

  * A execução desse script criará um banco de dados chamado `dataFlights` e importará os dados para a coleção `voos`.

⚠️ Como tanto esse script quanto o script de execução local dos testes (mostrado na [seção seguinte](#implementações-técnicas)), **restauram a base de dados `dataFlights`**, se atente a salvar seu progresso nos arquivos de desafio! ⚠️
