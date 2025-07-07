## 📘 Descrição do Exercício

- Na implementação de um **Banco de Dados**, há uma restrição para que **no máximo 10 consultas** sejam realizadas simultaneamente, ao passo que **apenas 1 operação de escrita** (insert, update ou delete) pode ocorrer por vez.
- Caso uma **11ª consulta** tente ser realizada, ela deve ser **bloqueada** até que alguma das consultas em andamento finalize.
- No momento de uma **operação de escrita**, **nenhuma consulta** pode estar ativa no banco de dados.
- Implemente uma **classe que discipline o acesso** ao banco de dados, respeitando essas regras.
- Implemente as **4 operações CRUD**:
  - **Create**
  - **Read**
  - **Update**
  - **Delete**
- Crie um **programa de teste** que demonstre o funcionamento da(s) classe(s) implementadas.
